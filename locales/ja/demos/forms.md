<!SLIDE form=classinfo>
# 知人を作る
## お互いにもっと知り合おう

教室の仕立てを手伝ってくれるよう、自分自身について少し教えてください
あなたのニーズに合った経験。

howlong -> あなたはPuppetをどれくらい使っていますか? = {
    under -> 6か月未満
    6mo -> 約6ヶ月
    1yr -> 約1年
    2yr -> 2年ほど
    more -> Puppet Enterpriseがルークの目に輝く前に、私の芝生に行ってください。
}

job -> あなたの仕事の役割は何ですか？ =
    [] support -> テクニカルサポート
    [] sysadmin -> システム管理者
    [] dbadmin -> データベース管理
    [] developer -> 開発者
    [] management -> 管理


usedpe -> Puppet Enterpriseを使ったことがありますか？ = () はい () いいえ

prepared -> あなたはこのクラスの準備をしていますか？ = () はい () いいえ

~~~SECTION:notes~~~

Tell the class a little bit about yourself and your own background.

~~~FORM:classinfo~~~

~~~ENDSECTION~~~
