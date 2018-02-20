<!SLIDE >
# コードライブ実行中
## コードブロックに `execute`キーワードを追加する

    @@@ Ruby execute
    ['一', '二', '三'].collect do |item|
      puts item.upcase
    end

テキスト行も強調表示できます：

    @@@ Puppet execute
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # これは*文字列*でなければならないことに注意してください
        content => "これはエキサイティングなファイルです！\n",
      }
    }
    include foo
    
.break

    @@@ Shell execute
    cat /tmp/foo
