glTFのJSON部では、extentionsまたはextrasにて機能を拡張することができます。

# 参考

https://github.com/KhronosGroup/glTF/tree/master/extensions#extensions-vs-extras

# ExtensionsとExtrasの違い

Extensionsは、glTFの仕様をまとめているKhronos Groupと各種ベンダーが用意している機能拡張です。    
glTF本体の仕様に組み込まれてはいませんが、この拡張を読み込めるエンジンもいくつかあります。    
将来的にglTFの仕様に昇格する可能性もあります。    

KHR_xxxx となっているのが、Khronos Groupでの機能拡張となります。    
それ以外のベンダーの場合は自由に拡張できるというわけではなく、
申請する(pull request)必要があるようです。    

各種プロジェクト(アプリケーション)で独自の拡張を行う場合は、「Extras」を使用します。    
このextrasに関しては、ローカルなニッチな使用といえそうです。
