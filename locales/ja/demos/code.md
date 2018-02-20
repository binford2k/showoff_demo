<!SLIDE>
# コード例を追加する
## 構文の強調表示の組み込み

    @@@ Ruby
    ['一', '二', '三'].collect do |item|
      puts item.upcase
    end

テキスト行も強調表示できます：

    @@@ Puppet
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # これは*文字列*でなければならないことに注意してください
        content => "これはエキサイティングなファイルです！\n",
      }
    }
    include foo
