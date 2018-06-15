# テクノロジー（藤原） 授業 6/15

今日の授業で打ったコマンドをコピー＆ペーストしてください。

（`irb`や`ruby`の実行結果も含めて全てをコピーしてください）

## ターミナルに打ったコマンド

```
print("Hello,Ruby. \n")

$ ruby helloruby.rb
Hello,Ruby.
```



```
$ irb
irb(main):001:0> print("Hello,Ruby. \n")
Hello,Ruby.
=> nil
irb(main):002:0> 1 + 1
=> 2
irb(main):003:0> "Hello,Ruby.\n"
=> "Hello,Ruby.\n"
irb(main):004:0> "Hello,Ruby.\n".class
=> String
irb(main):005:0> (1 + 1).class
=> Integer
irb(main):006:0> ^D
$ irb --simple-prompt
>> 1
=> 1
>> 1.class
=> Integer
>> 3.1415
=> 3.1415
>> (3.1415).class
=> Float
>> ^D
$ irb
irb(main):001:0> 10.times do
irb(main):002:1* print "Hello,Ruby.\n"
irb(main):003:1> end
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
Hello,Ruby.
=> 10
irb(main):004:0>
```
