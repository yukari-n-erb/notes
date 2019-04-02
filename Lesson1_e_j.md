# Lesson 1
[Webpage](http://course-v3.fast.ai/) / [Video](https://youtu.be/BWWm4AzsdLk) /  [Lesson Forum](https://forums.fast.ai/t/lesson-1-official-resources-and-updates/27936) / [General Forum](https://forums.fast.ai/t/faq-resources-and-official-course-updates/27934/1)



## Welcome! ようこそ！

Make sure your GPU environment is set up and you can run Jupyter Notebook

GPU環境を構築してJupyter Notebookを起動できるようにしてください

[00_notebook_tutorial.ipynb](https://github.com/fastai/course-v3/blob/master/nbs/dl1/00_notebook_tutorial.ipynb)


Four shortcuts:

4個のショートカット：

- <kbd>Shift</kbd>+<kbd>Enter</kbd>: Runs the code or markdown on a cell

コードを実行するか下のセルへ移動する

- <kbd>Up Arrow</kbd>+<kbd>Down Arrow</kbd>: Toggle across cells

セルを切り替える

- <kbd>b</kbd>: Create new cell

新しいセルを作成する

- <kbd>0</kbd>+<kbd>0</kbd>: Restart Kernel

カーネルを再起動する


[[2:45](https://youtu.be/BWWm4AzsdLk?t=165)] 

Jupyter Notebook is a really interesting device for data scientists because it lets you run interactive experiments and give you not just a static piece of information but something you can interactively experiment with.

Jupyter Notebookはデータサイエンティストにとって大変面白いデバイスです。なぜなら対話的な実験を行うことができ、静的な情報だけでなく対話的に実験した情報も得ることができるからです。

How to use notebooks and the materials well based on the last three years of experience:

過去3年間の講義に基づいたこのノートと資料の使用方法

1. Just watch a lesson end to end. 講義を一通り視聴する
   - Don't try to follow along because it's not really designed to go the speed where you can follow along. It's designed to be something where you just take in the information, you get a general sense of all the pieces, how it all fits together.話についていこうとしてはいけません、なぜなら講義はあなたがついていけるスピードで設計されていません。どのような仕組みになっているのか、全体的な概要を知ることを想定しています。
   - Then you can go back and go through it more slowly pausing the video, trying things out, making sure that you can do the things that I'm doing and you can try and extend them to do things in your own way.その後、改めて動画をゆっくりと一時停止しながら確認し、実際に実行して確認し、また自分なりのやり方で拡張してみましょう。
   - Don't try and stop and understand everything the first time. 一回で全てを理解しようとしてはいけません。



### You can do world-class practitioner level deep learning 世界クラスの専門家並のディープラーニングができる[[4:31](https://youtu.be/BWWm4AzsdLk?t=271)]

![](lesson1/1.png)

Main places to be looking for things are: 資料の主な場所:
- [http://course-v3.fast.ai/](http://course-v3.fast.ai/)
- [https://forums.fast.ai/](https://forums.fast.ai/latest)





### A little bit about why we should listen to Jeremy ジェレミーについて少しご紹介 [[5:27](https://youtu.be/BWWm4AzsdLk?t=327)]

![](lesson1/2.png)





### Using machine learning to do useful things　マシンラーニングを使うために役立つこと  [[6:48](https://youtu.be/BWWm4AzsdLk?t=408)]

![](lesson1/3.png)



[[7:26](https://youtu.be/BWWm4AzsdLk?t=446)]

![](lesson1/4.png)

If you follow along with 10 hours a week or so approach for the 7 weeks, by the end, you will be able to:

１週ごとに10時間復習し、7週間講義を終えると、次のことが可能になります:

1. Build an image classification model on pictures that you choose that will work at a world class level
あなたが選んだ写真で、世界クラスレベルの画像識別モデルを作成できます
2. Classify text using whatever datasets you're interested in
あなたの興味があるデータセットを利用した文章分類
3. Make predictions of commercial applications like sales
商用アプリケーションのような売り上げ予測
4. Build recommendation systems such as the one used by Netflix
Netflixのような推薦システム

Not toy examples of any of these but actually things that can come top 10 in Kaggle competitions, that can beat everything that's in the academic community. 

これらはおもちゃようなものではなく実際にKaggleの大会でトップ10に入ることのできるような、学術界隈のすべてのものに勝るようなものです。


The prerequisite is one year of coding and high school math.

受講の前提条件1年間のコーディング経験と高校レベルの数学です。


### What people say about deep learning which are either pointless or untrue ディープラーニングに対して言われる無意味な批判または正しくないこと [[9:05](https://youtu.be/BWWm4AzsdLk?t=545)]

![](lesson1/5.png)

- It's not a black box. It's really great for interpreting what's going on.
ブラックボックスではありません。何が起きたのかを解釈することは本当に素晴らしいことです。
- It does not need much data for most practical applications.
大半の実用的なアプリケーションには大量のデータは必要ありません。
- You don't need a PhD. Rachel has one so it doesn't actually stop you from doing deep learning if you have a PhD.
博士号は必要ありません。レイチェルは博士号を持っていますので、もしあなたが博士号を持っていてもディープラーニングをすることを妨げることはありません。
- It can be used very widely for lots of different applications, not just for vision.
たくさんの異なる幅広いアプリケーションに利用できます、決して画像認識だけではありません。
- You don't need lots of hardware. 36 cents an hour server is more than enough to get world-class results for most problems.
ハードウェアは必要ありません。ほとんどの問題に対して世界クラスの成果を出すためには、一時間あたり36セントのサーバーで十分です。
- It is true that maybe this is not going to help you build a sentient brain, but that's not our focus. We are focused on solving interesting real-world problems.
これで知性のある頭脳を作れるわけではないのということは本当ですが、しかし関心があることはそこではありません。我々は現実世界の興味深い問題を解決することに焦点を当てています。



[[10:24](https://youtu.be/BWWm4AzsdLk?t=624)]

![](lesson1/6.png)

Baseball vs. Cricket - An example by Nikhil of what you are going to be able to do by the end of lesson 1:

野球　VS　クリケット　-　ニヒルによる、レッスン1の完了までにあなたができるようになることの一例


### Topdown approach トップダウンアプローチ [[11:02](https://youtu.be/BWWm4AzsdLk?t=662)]

![](lesson1/7.png)

We are going to start by looking at code which is different to many of academic courses. We are going to learn to build a useful thing today. That means that at the end of today, you won't know all the theory. There will be lots of aspects of what we do that you don't know why or how it works. That's okay! You will learn why and how it works over the next 7 weeks. But for now, we've found that what works really well is to actually get your hands dirty coding - not focusing on theory. 

我々は多くのほかのアカデミックな講義とは違い、実際にコードを見ていくことから始めます。実用的なものを作ることを今日は学びます。これはつまり今日の講義が終わった段階では、あなたはすべての理論を知らないということです。それがなぜどのように動くのかを理解できないままでしょう。それでOK!なぜ・どのように動くのかは次の7週間で学びます。今は、自分の手で綺麗ではない - 理論に基づかない - コードを書くことが本当に良いことであるとが分かるようになるでしょう。



## What's your pet どれがあなたのペット [[12:26](https://youtu.be/BWWm4AzsdLk?t=746)]

[lesson1-pets.ipynb](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson1-pets.ipynb)

<kbd>Shift</kbd>+<kbd>Enter</kbd> to run a cell セルを実行します

These three lines is what we start every notebook with: 毎回ノートブックを開始する際の3行のコード
```
%reload_ext autoreload
%autoreload 2
%matplotlib inline
```
These things starting `%` are special directives to Jupyter Notebook itself, they are not Python code. They are called "magics."

 `%` で始まるものはPythonコードではないJupyter Notebook自身に対する命令で、”マジック”と呼ばれるものです。

- If somebody changes underlying library code while I'm running this, please reload it automatically
実行中のライブラリに変更があったら、自動的に再読みする
- If somebody asks to plot something, then please plot it here in this Jupyter Notebook
プロットに関して問い合わせがあったら、このJupyter Notebookに対してプロットする

The next two lines load up the fastai library: 次の二行でfastaiライブラリを読み込む:

```python
from fastai import *
from fastai.vision import *
```

What is fastai library? fastaiライブラリとは？ [http://docs.fast.ai/](http://docs.fast.ai/)

Everything we are going to do is going to be using either fastai or [PyTorch](https://pytorch.org/) which fastai sits on top of. PyTorch is fast growing extremely popular library. We use it because we used to use TensorFlow a couple years ago and we found we can do a lot more, a lot more quickly with PyTorch. 

これから実行しようとするものは全てfastaiか[PyTorch](https://pytorch.org/)上で実行されます。PyTorchは急速に成長している極めてポピュラーなライブラリです。二年前まではTensorFlowを利用していましたが、PyTorchのほうが更に手早く物事を実行できるためにこれを利用しています。



Currently fastai supports four applications: 現在fastaiがサポートする4つのアプリケーション:

1. Computer vision
コンピュータビジョン
2. Natural language text
自然言語文章
3. Tabular data
表形式データ
4. Collaborative filtering
協調フィルタリング


[[15:45](https://youtu.be/BWWm4AzsdLk?t=945)]

`import *` - something you've all been told to never ever do. あなたが決してしないように言われたこと

There are very good reasons to not use `import *` in standard production code with most libraries. But things like MATLAB is the opposite. Everything is there for you all the time. You don't even have to import things a lot of the time. It's kind of funny - we've got these two extremes of how do I code. The scientific programming community has one way, and then software engineering community has the other. Both have really good reasons for doing things. 

 ほとんどのライブラリでは標準的に`import *`を使わないようにとされているのはとても良い理由があります。しかしMATLABのようなものは反対です。すべてのことはあなたのためにあります。あなたは多くの時間をインポートすることに割くべきではない。でもこれはすこしおかしい - これはどのようにコーディングすべきかということに対する正反対のことです。科学プログラミングコミュニティにはある一つの手法があります、しかしエンジニアリングコミュニティにもまた同じようにあります。二つともそうる良い理由があるのです。

With the fastai library, we actually support both approaches. In Jupyter Notebook where you want to be able to quickly interactively try stuff out, you don't want to constantly going back up to the top and importing more stuff. You want to be able to use lots of tab complete and be very experimental, so `import *` is great. When you are building stuff in production, you can do the normal PEP8 style proper software engineering practices. This is a different style of coding. It's not that there are no rules in data science programming, the rules are different. When you're training models, the most important thing is to be able to interactively experiment quickly. So you will see we use a lot of different processes, styles, and stuff to what you are used to. But they are there for a reason and you'll learn about them over time. 

fastaiライブラリでは、どちらの手法もサポートしました。対話的にたくさんのことを試したいJupyter Notebook上では、あなたは常に上へ戻って更に沢山のインポートをしたくはないでしょう。あなたが多くのタブを開いて実験を比較するなら、`import *` することがいいでしょうあなたが多くのものを作り出したいときには、ソフトウェアエンジニアリングの知見に基づいたPEP8コーディング規約で行うでしょう。これは異なるスタイルのコーディング手法です。データサイエンスプログラミングではルールがないわけではなありません、ルールが異なるだけです。モデルを訓練するとき、最も関心があることは素早く対話的に実験ができるかということです。なので、私たちはあなたが使い慣れているプロセス・スタイル・その他たくさんのものとは違うものが使われているのをみるでしょう。しかし、それらには理由があり、時間とともにそれを学んでいくでしょう。

The other thing to mention is that the fastai library is designed in a very interesting modular way and when you do use import *, there's far less clobbering of things than you might expect. It's all explicitly designed to allow you to pull in things and use them quickly without having problems.

もう一つ取り上げることとして、fastaiライブラリは興味深いモジュラー方式で設計されており、import * を使う場面はあなたの予想より遥かに少ないでしょう。これはあなたが何事も問題なく実行できるように全て明確に設計されているからです。


## Looking at the data データを見る [[17:56](https://youtu.be/BWWm4AzsdLk?t=1076)]

Two main places that we will be tending to get data from for the course: このコースでデータを取得しにいく傾向がある二つの場所

1. Academic datasets アカデミックデータシート
    - Academic datasets are really important. They are really interesting. They are things where academics spend a lot of time curating and gathering a dataset so that they can show how well different kinds of approaches work with that data. The idea is they try to design datasets that are challenging in some way and require some kind of breakthrough to do them well. 
    アカデミックデータシートはとても重要です。ここは本当に興味深い。このアカデミックではデータに対して様々な手法がどのように働くかを示すデータセットを収集・整理することにたくさんの時間を費やしています。このアイデアは、データセットにチャレンジして様々なブレイクスルーを起こすようにするために設計されています。
    - We are going to start with an academic dataset called the pet dataset.
    私たちはアカデミックデータセットの「ペットデータセット」と呼ばれるものから始めます。
2. Kaggle competition datasets　Kaggle大会のデータセット
 

Both types of datasets are interesting for us particularly because they provide strong baseline. That is to say you want to know if you are doing a good job. So with Kaggle datasets that come from a competition, you can actually submit your results to Kaggle and see how well you would have gone in that competition. If you can get in about the top 10%, then I'd say you are doing pretty well.

どちらのデータでっとも私たちに強力な基準を提供するという意味で非常に興味深いです。それはあなたが良い結果を出せたかどうかを知りたいということです。Kaggleの大会でのデータセットでは、あなたは実際に結果をKaggleに提出して、そのコンペでどれだけ上手くやれたかを知ることができます。もしトップ10%以内にいるのなら、非常によくできたと言えるでしょう。


Academic datasets, academics write down in papers what the state of the art is so how well did they go with using models on that dataset. So this is what we are going to do. We are going to try to create models that get right up towards the top of Kaggle competitions, preferably in the top 10, not just top 10% or that meet or exceed academic state-of-the-art published results. So when you use an academic dataset, it's important to cite it. You don't need to read that paper right now, but if you are interested in learning more about it and why it was created and how it was created, all the details are there. 

アカデミックデータシートでは、最先端の論文にそのデータセットにおいてどのようなモデルが使われたかが記載されています。それが私たちが今からやろうとしていることです。私たちはKaggleのコンペでトップ10%ではなくトップに入ったり、アカデミックの最先端の結果を上回すモデルを作ることにチャレンジします。そのあめ、アカデミックデータシートを使用するときは、それを引用することが大切です。今はまだその論文を読む必要はありませんが、もしあなたがそれがなぜどのように作られたかに関心を持ったとき、その詳細がそこにあるからです。

Pet dataset is going to ask us to distinguish between 37 different categories of dog breed and cat breed. So that's really hard. In fact, every course until this one, we've used a different dataset which is one where you just have to decide if something is a dog or a cat. So you've got a 50-50 chance right away and dogs and cats look really different. Or else lots of dog breeds and cat breeds look pretty much the same. 

ペットデータセットでは37種類の犬と猫の品種を分類するように求められます。これはとても難しいことです、実際、これより前のコースでは、私たちは犬か猫かだけを分類するという違うデータセットを使用していました。これは半々の確率であり、実際犬と猫は本当に異なっているように見えます。他方、多くの犬種と猫種は同じように見えます。

So why have we changed the dataset? We've got to the point now where deep learning os so fast and so easy that the dogs versus cats problem which a few years ago was considered extremely difficult ~80% accuracy was the state of the art, it's now too easy. Our models were basically getting everything right all the time without any tuning and so there weren't really a lot of opportunities for me to show you how to do more sophisticated stuff. So we've picked a harder problem this year. 

なぜデータセットを変えたのか？犬と猫を素早く簡単に分類できることは数年前まではとても難しく、実際最先端の結果えも80%程度までの精度しかなかったが、現在では非常に簡単です。私たちのモデルは基本的に調整しなくとも上手くいっていたので、もっと洗練された手法を見せる機会があまりありませんでした。そこで、今年はもっと難しい問題を選んだのです。

[[20:51](https://youtu.be/BWWm4AzsdLk?t=1251)]

This kind of thing where you have to distinguish between similar categories is called fine grained classification in the academic context.  

似たようなカテゴリを分類することは、学術用語で「細粒度分類」と言います。

### untar_data

The first thing we have to do is download and extract the data that we want. We're going to be using this function called `untar_data` which will download it automatically and untar it. AWS has been kind enough to give us lots of space and bandwidth for these datasets so they'll download super quickly for you.

最初にデータをダウンロードして任意の場所に展開します。`untar_data` と呼ばれる関数を使うとダウンロードしたものを自動的に展開します。AWSはこれらのデータセットを利用するために十分な容量と帯域幅を確保してくれているので、すぐに完了するでしょう。

```python
path = untar_data(URLs.PETS); path
```

### help 

The first question then would be how do I know what `untar_data` does. You could just type help and you will find out what module it came from (since we did `import *` you don't necessarily know that), what it does, and something you might not have seen before even if you are an experienced programmer is what exactly you pass to it. You're probably used to seeing the names: url, fname, dest, but you might not be used to seeing `Union[pathlib.Path, str]`. These bits are types and if you're used to typed programming language, you would be used to seeing them, but Python programmers are less used to it. But if you think about it, you don't actually know how to use a function unless you know what type each thing is that you're providing it. So we make sure that we give you that type information directly here in the help. 

最初の疑問は、`untar_data` がどのような働きをするのかをどうやって知ればいいのかということでしょう。helpと入力すればそれがどのモジュールから来たのか（`import *`をしたので、必ずしもあなたはそれがどこから来たものか知っている必要はない）、そしてそれが何をするのか、仮にあなたが経験豊富なプログラマーであっても知らないものを渡すかもしれない。おそらくあなたはurl,frame,destといった名称を見たことがあるでしょうが、`Union[pathlib.Path, str]`という表記は見慣れないかもしれません。これらの形式は型付きプログラミング言語を経験したことがあるなら見慣れているでしょうか、Pythonプログラマーにとっては見慣れないものでしょう。しかしこれについて考えたとき、実際にはあなたが使うとしているものがどんな型であるかを知らない限り使い方はわからないでしょう。そこで、ここではhelpで直接その型についての情報を提供しています。

In this case, `url` is a string, `fname` is either path or a string and defaults to nothing (`Union` means "either"). `dest` is either a string or a path and defaults to nothing. 

このケースでは、`url`は文字列、`fname`はパスまたは文字列で、標準では不要（`Union`の意味は”どちらでも”）、`dest`は文字列またはパスで標準では不要なものです。

```python
help(untar_data)
```

```
Help on function untar_data in module fastai.datasets:

untar_data(url:str, fname:Union[pathlib.Path, str]=None, dest:Union[pathlib.Path, str]=None)
    Download `url` if doesn't exist to `fname` and un-tgz to folder `dest`
```

We'll learn more shortly about how to get more documentation about the details of this, but for now, we can see we don't have to pass in a file name `fname` or a destination `dest`, it'll figure them out for us from the URL. 

このドキュメントの詳細は後ほど学びますが、今のところ`fname` と`dest`は必ずしも渡す必要はないこと、URLが必要なことがわかります。

For all the datasets we'll be using in the course, we already have constants defined for all of them. So in this [URLs](https://github.com/fastai/fastai/blob/master/fastai/datasets.py) class, you can see where it's going to grab it from.

この講義で使用する予定のデータセットには既に定義済みの値があります。このURLのクラスからは、その値がどこからきたものかがわかります。

`untar_data` will download that to some convenient path and untar it for us and it will then return the value of path. 

`untar_data`は便利な場所にデータをダウンロードし、その場所のPATHを返します。

```python
path = untar_data(URLs.PETS); path
```
```
PosixPath('/data1/jhoward/git/course-v3/nbs/dl1/data/oxford-iiit-pet')
```
In Jupyter Notebook, you can just write a variable on its own (semicolon is just an end of statement in Python) and it prints it. You can also say `print(path)` but again, we are trying to do everything fast and interactively, so just write it and here is the path where it's given us our data. 

Jupyter Notebookでは自分自身で変数を定義することができ（セミコロンはPython文の終わりを示しています）、そしてそれを表示できます。
 `print(path)` と書くこともできますが、繰り返しますが私達はすべてをすばやくインタラクティブに行いたいので、変数を書くだけでそのデータを表示します。

Next time you run this, since you've already downloaded it, it won't download it again. Since you've already untared it, it won't untar it again. So everything is designed to be pretty automatic and easy.

これを次に実行したときには、それは既にダウンロードし終えているので、再びダウンロードｓる必要はありません。既に解凍済みなので再び解凍する必要もありません。すべてが自動的かつ簡単にできるように設計されています。

[[23:50](https://youtu.be/BWWm4AzsdLk?t=1430)]

There are some things in Python that are less convenient for interactive use than they should be. For example, when you do have a path object, seeing what's in it actually takes a lot more typing than I would like. So sometimes we add functionality into existing Python stuff. One of the things we do is add a `ls()` method to path.

Pythonにはいくつか対話的に利用するには不向きな点があります。例えば、pathのオブジェクトがあったとき、その中になにがあるかを見るには私が望むよりさらに多くのタイピングが必要です。そのため、ときどき既存のPythonの機能に追加をします。その一つは、Pathにls()メソッドを追加することです。

```python
path.ls()
```
```
['annotations', 'images']
```

These are what's inside this path, so that's what we just downloaded. 

これがこのPathの中に存在しているものです。先ほどダウンロードしたデータが格納されています。

### Python 3 pathlib [[24:25](https://youtu.be/BWWm4AzsdLk?t=1465)]

```python
path_anno = path/'annotations'
path_img = path/'images'
```

If you are an experienced Python programmer, you may not be familiar with this approach of using a slash like this. This is a really convenient function that's part of Python 3. It's functionality from [pathlib](https://docs.python.org/3/library/pathlib.html). Path object is much better to use than strings. They let you use basically create sub paths like this. It doesn't matter if you're on Windows, Linux, or Mac. It is always going to work exactly the same way. `path_img` is the path to the images in that dataset.

あなたがPythonプログラマーとしての経験があったとしても、このようにスラッシュを使った記法は知らないでしょう。これは本当にPython3における便利な機能です。この機能はpathlibから来ています。Pathオブジェクトは文字列よりも遥かに使いやすいです。これらはあなたが基本的なサブバスをこのように作ることができます。Windows,Linux,Macでもかまいません。これらは同じように動くでしょう。`path_img` は画像のデータセットへのパスです。

[[24:57](https://youtu.be/BWWm4AzsdLk?t=1497)]

So if you are starting with a brand new dataset trying to do some deep learning on it. What do you do? Well, the first thing you would want to do is probably see what's in there. So we found that `annotations` and `images` are the directories in there, so what's in this images? 

そしてこの新しいデータセットでディープラーニングの学習を始めるにはどうしたらいいと思いますか？まずは、最初にすることはおそらく画像の中身を見ることでしょう。 `annotations` と `images` のフォルダがあることはわかりました。この画像はいったいなんでしょうか？

### get_image_files [[25:15](https://youtu.be/BWWm4AzsdLk?t=1515)]

get_image_files will just grab an array of all of the image files based on extension in a path. 

get_image_filesはパス内の拡張子に基づいて画像ファイルの配列を返すだけです。

```python
fnames = get_image_files(path_img)
fnames[:5]
```
```
[PosixPath('/data1/jhoward/git/course-v3/nbs/dl1/data/oxford-iiit-pet/images/american_bulldog_146.jpg'),
 PosixPath('/data1/jhoward/git/course-v3/nbs/dl1/data/oxford-iiit-pet/images/german_shorthaired_137.jpg'),
 PosixPath('/data1/jhoward/git/course-v3/nbs/dl1/data/oxford-iiit-pet/images/japanese_chin_139.jpg'),
 PosixPath('/data1/jhoward/git/course-v3/nbs/dl1/data/oxford-iiit-pet/images/great_pyrenees_121.jpg'),
 PosixPath('/data1/jhoward/git/course-v3/nbs/dl1/data/oxford-iiit-pet/images/Bombay_151.jpg')]
```

 This is a pretty common way for computer vision datasets to get passed around - just one folder with a whole bunch of files in it. So the interesting bit then is how do we get the labels. In machine learning, the labels refer to the thing we are trying to predict. If we just eyeball this, we could immediately see that the labels are actually part of the file names. It's kind of like `path/label_number.extension`. We need to somehow get a list of `label` bits of each file name, and that will give us our labels. Because that's all you need to build a deep learning model:
 - Pictures (files containing the images)
 - Labels
 
 これはコンピュータビジョンにおけるデータセットのパスを得るための非常に一般的な方法です。 - 一つのフォルダの中にあるたくさんのファイルを渡すための。これの興味深い点はラベルを得るための方法です。機械学習では、ラベルとは我々が予測したいことを指します。しかし実際に見てみると、これはラベルがファイルパスの一部となっていることがわかります。`path/label_number.extension` といったように。私達はこのラベルの列をファイル名から取得し我々のラベルとする必要があるのでしょう。ディープラーニングのモデル作成に必要なのは次のものだけです：
  - 写真 (画像を含むファイル)
  - ラベル
 

In fastai, this is made really easy. There is an object called `ImageDataBunch`. An ImageDataBunch represents all of the data you need to build a model and there's some factory method which try to make it really easy for you to create that data bunch - a training set, a validation set with images and labels. 

fastaiでは、これは非常に簡単です。これは`ImageDataBunch`（画像データ集）と呼ばれます。画像データ集はあなたのモデル作成に必要なものをすべて含んでおり、データ集を簡単に作るためのいくつかの工場のような手段 - 訓練セット、評価セット、イメージラベル - があります。

In this case, we need to extract the labels from the names. We are going to use `from_name_re`. `re` is the module in Python that does regular expressions - things that's really useful for extracting text. 

このケースでは、ファイルネームからラベルを展開する必要があります。`from_name_re`を利用します。`re`はPythonの正規表現を使えるようにするモジュールで - これは文字列を展開するのに本当に便利なのです。

Here is the regular expression that extract the label for this dataset:

ここではこのデータセットから正規表現でラベルを展開してみましょう。

```python
np.random.seed(2)
pat = r'/([^/]+)_\d+.jpg$'
```
With this factory method, we can basically say:

この手法では私達はいつも下記のように言っています。

- path_img: a path containing images
- fnames: a list of file names
- pat: a regular expression (i.e. pattern) to be used to extract the label from the file name
- ds_tfm: we'll talk about transforms later
- size: what size images do you want to work with.
  
  
- path_img: 画像を含むパス
- fnames: ファイル名のリスト
- pat: ファイル名からラベルを展開するために利用する基本的な正規表現（例）
- ds_tfm: 展開については後ほど説明します。
- size: どんなサイズの画像を使用したいか

This might seem weird because images have size. This is a shortcoming of current deep learning technology which is that a GPU has to apply the exact same instruction to a whole bunch of things at the same time in order to be fast. If the images are different shapes and sizes, you can't do that. So we actually have to make all of the images the same shape and size. In part 1 of the course, we are always going to be making images square shapes. Part 2, we will learn how to use rectangles as well. It turns out to be surprisingly nuanced. But pretty much everybody in pretty much all computer vision modeling nearly all of it uses this approach of square. 224 by 224, for reasons we'll learn about, is an extremely common size that most models tend to use so if you just use size=224, you're probably going to get pretty good results most of the time. This is kind of the little bits of artisanship that I want to teach you which is what generally just works. So if you just use size 224, that'll generally just work for most things most of the time.


画像にサイズという項目があるのは不自然に見えるかもしれません。これは現在のディープラーニング技術の欠点のせいで、高速な処理のためにはGPUが同じ命令を同時に実行できるようにする必要があるからです。もし画像の形や大きさが違っていたらそれができないのです。そのため、実際にはすべての画像の形とサイズを同じにする必要があります。このPart1のコースでは、いつも画像の形は正方形にします。Part2では長方形の処理の仕方も学びます。驚くほど奇妙な違いがあることがわかるでしょう。しかしほとんどのコンピュータビジョンモデリングを行う人々は224×224の正方形を利用しています、その理由はほとんどのモデルが使う傾向のある224のサイズを採用しているからで、そうすることえあなたも多くの場合においていい結果が得られるでしょう。これはあなたに教えておきたい、一般的に上手くいくためのコツのようなものです。もしあなたが224のサイズを使うなら、それはほとんどの場合で上手く行く結果が得られるでしょう。

```python
data = ImageDataBunch.from_name_re(path_img, fnames, pat, ds_tfms=get_transforms(), size=224)
data.normalize(imagenet_stats)
```

[[29:16](https://youtu.be/BWWm4AzsdLk?t=1756)]

`ImageDataBunch.from_name_re` is going to return a DataBunch object. In fastai, everything you model with is going to be a DataBunch object. Basically DataBunch object contains 2 or 3 datasets - it contains your training data, validation data, and optionally test data. For each of those, it contains your images and your labels, your texts and your labels, or your tabular data and your labels, or so forth. And that all sits there in this one place(i.e. `data`). 

`ImageDataBunch.from_name_re`はデータ集合のオブジェクトを返します。fastaiでは、すべてのモデルはデータ集合オブジェクトになります。基本的にデータ集合オブジェクトは2個から3個のデータセットを持ちます - それは訓練データ、評価データ、そしてオプションのテストデータです。それぞれのデータセットには画像とラベル、テキストとラベル、表データとラベルといったものが含まれています。そしてその全てがこの一箇所にあるのです。（例えば `data`)）

Something we will learn more about in a little bit is normalization. But generally in nearly all machine learning tasks, you have to make all of your data about the same "size" - they are specifically about the same mean and standard deviation.  So there is a normalize function that we can use to normalize our data bunch in that way.

ここで正規化についてもう少し詳しく説明します。しかし一般的なほとんどすべての機械学習タスクにおいて、あなたは同じサイズのデータを作らねばなりません - それらは同じ平均と標準偏差のことです。そのため、データを正規化するために使える正規化関数について説明します。

`ImageDataBunch.from_name_re`

[[30:25](https://youtu.be/BWWm4AzsdLk?t=1825)]

Question: What does the function do if the image size is not 224? 

質問:もし画像サイズが224でないときに実行するとこの関数は何をしますか？

This is what we are going to learn about shortly. Basically this thing called transforms is used to do a number of the things and one of the things it does is to make something size 224. 

これをこのあと学びます。基本的には変換と呼ばれる処理は様々なことをしていますが、その一つがサイズを224にすることです。


### data.show_batch
Let's take a look at a few pictures. Here are a few pictures of things from my data bunch. So you can see data.show_batch can be used to show me some of the contents in my data bunch. So you can see roughly what's happened is that they all seem to have being zoomed and cropped in a reasonably nice way. So basically what it'll do is something called by default center cropping which means it'll grab the middle bit and it'll also resize it. We'll talk more about the detail of this because it turns out to actually be quite important, but basically a combination of cropping and resizing is used.

いくつかの写真を見てみましょう。 これが私のデータ集の中のいくつかの写真です。 あなたはdata.show_batchがデータ集のなかのいくつかのコンテンツを表示するために使われることがわかるでしょう。それらがかなり合理的にズームまたは切り取られているということがだいたいの写真で起こっていることが分かるでしょう。 これは基本的にはデフォルトのセンタークロッピングと呼ばれるもので、それは中央を中心にサイズ変更するということです。 これらについては実際には非常に重要であるので詳しく説明しますが、基本的にはトリミングとサイズ変更の組み合わせが使用されます。

```python
data.show_batch(rows=3, figsize=(7,6))
```
![](lesson1/8.png)

Something else we are going to learn about is we also use this to do something called data augmentation. So there's actually some randomization in how much and where it crops and stuff like that. 

他に学ぶこととして、これを使ってデータ拡張と呼ばれることをすることです。これはいくつかランダムな大きさや場所で切り取りすることです。

Basic the basic idea is some cropping, resizing, and padding. So there's all kinds of different ways it depends on data augmentation which we are going to learn about shortly. 

基本的な考え方は、トリミング、サイズ変更、パディングです。データ拡張に関する様々な手法については近々学びます。

[[31:51](https://youtu.be/BWWm4AzsdLk?t=1911)]

**Question**: What does it mean to normalize the images? 
画像を正規化するとはどういう意味ですか？

Normalizing the images, we're going to be learning more about later in the course, but in short, it means that the pixel values start out from naught to 255. And some channels might tend to be really bright, some might tend to be really not bright at all, some might vary a lot, and some might not very much at all. It really helps train a deep learning model if each one of those red green and blue channels has a mean of zero and a standard deviation of one. 赤、緑、青の各チャンネルの平均が0で標準偏差が1の場合であれば、ディープラーニングモデルの訓練に非常に役立ちます。

画像の正規化についてはコースの後半で学びますが、それはつまりピクセル値が0から255であるということです。いくつかのチャンネルは明るくなるかもしれませんし全く明るくならないかもしれませんし、あるものは大きく変わるかもしれませんし全く変わらないかもしれません。

If your data is not normalized, it can be quite difficult for your model to train well. So if you have trouble training a model, one thing to check is that you've normalized it.

もしあなたのデータが正規化されていなければ、あなたのモデルを上手に訓練するのは少し難しいかもしれません、もしあなたがモデルの訓練に問題を抱えていたら、一度正規化についてチェックするといいでしょう。

[[33:00](https://youtu.be/BWWm4AzsdLk?t=1980)]
**Question**: As GPU mem will be in power of 2, doesn't size 256 sound more practical considering GPU utilization compared to 224?
GPUのメモリ容量は2のべき乗になるので、224より256のほうがGPUの使用効率を考えると実用的なのではないでしょうか？

The brief answer is that the models are designed so that the final layer is of size 7 by 7, so we actually want something where if you go 7 times 2 a bunch of times (224 = 7*2*2*2*2*2), then you end up with something that's a good size.

簡単に答えると、これは最終的なレイヤーのサイズが7×7になるようにモデルが設計されているからで、実際には7×2を行った場合(224 = 7*2*2*2*2*2)、いいサイズのものが得られるようになっています。（※原文チェック）

[[33:27](https://youtu.be/BWWm4AzsdLk?t=2007)]

We will get to all these details but the key thing is I wanted to get to training a model as quickly as possible. 

これから詳細を知ることになるでしょうが、しかし大切なことは私はモデルの訓練をできるだけ早く訓練できるようになってほしいということです。

### It is important to look at the data
データを見ることは重要

One of the most important thing to be a really good practitioner is to be able to look at your data. So it's really important to remember to go to `data.show_batch` and take a look. It's surprising how often when you actually look at the dataset you've been given that you realize it's got weird black borders on it, some of the things have text covering up some of it, or some of it is rotated in odd ways. So make sure you take a look.

本当に優秀な専門家になるために大切なことは、データを見ることができるようになることです。  `data.show_batch`で見ることを忘れないことはとても重要です。 データセットを実際に見るてみと、黒い境界線が入っていたり、テキストの一部が隠れていたり、または一部が奇妙に回転していることに気付きます。だから実際に見てみることはとても重要です。


The other thing we want to do is to look at the labels. All of the possible label names are called your classes. With DataBunch, you can print out your `data.classes`.

他にしたいことはラベルを確認することです。ラベルとして利用可能な名前の全てはクラスと呼ばれます。 DataBunchを使えばあなたの`data.classes`を表示することができます。

```python
print(data.classes)
len(data.classes),data.c
```

```
['american_bulldog', 'german_shorthaired', 'japanese_chin', 'great_pyrenees', 'Bombay', 'Bengal', 'keeshond', 'shiba_inu', 'Sphynx', 'boxer', 'english_cocker_spaniel', 'american_pit_bull_terrier', 'Birman', 'basset_hound', 'British_Shorthair', 'leonberger', 'Abyssinian', 'wheaten_terrier', 'scottish_terrier', 'Maine_Coon', 'saint_bernard', 'newfoundland', 'yorkshire_terrier', 'Persian', 'havanese', 'pug', 'miniature_pinscher', 'Russian_Blue', 'staffordshire_bull_terrier', 'beagle', 'Siamese', 'samoyed', 'chihuahua', 'Egyptian_Mau', 'Ragdoll', 'pomeranian', 'english_setter']

(37, 37)
```

 That's all of the possible labels that we found by using that regular expression on the file names. We learnt earlier on at the top that there are 37 possible categories, so just checking `len(data.classes)`, it is indeed 37. DataBunch will always have a property called `c`. We will get to the technical detail later, but for now, you can kind of think of it as being the number of classes. For things like regression problems and multi-label classification, that's not exactly accurate, but it'll do for now. It is important to know that `data.c` is a really important piece of information that is something like, or at least for classification problems it is, the number of classes. 

これが、ファイル名から正規表現を使用して取得した利用可能なラベル名のすべてです。 授業のの冒頭で37のカテゴリーがあると説明しましたが `len（data.classes）`をチェックと確かに37個あります。DataBunchは常に `c`というプロパティがあります。 技術的な詳細については後で説明しますが、今のところ、それはクラスの数であると考えてください。 回帰問題やマルチラベル分類などに関してはそれは正確ではありませんが、今のところはそう考えてください。 `data.c`は本当に重要な情報です、少なくとも分類問題においてこれはクラスの数ですから。

 ## Training [[35:07](https://youtu.be/BWWm4AzsdLk?t=2107)]
訓練

 Believe it or not, we are now ready to train a model. A model is trained in fastai using something called a "learner". 

信じられないかもしれませんが、これでモデルを訓練する準備が整いました。 fasraiではモデルは「学習器」と呼ばれるものを使って訓練されます。

 - **DataBunch**: A general fastai concept for your data, and from there, there are subclasses for particular applications like ImageDataBunch
 fastaiにおける一般的なデータの概念では、ImageDataBunchのような特別なアプリケーションのためのサブクラスがあります
 
 - **Learner**: A general concept for things that can learn to fit a model. From that, there are various subclasses to make things easier in particular, there is a convnet learner  (something that will create a convolutional neural network for you).
モデルに適合するように訓練するための一般的な概念。 そこれには特に物事を簡単にするためのさまざまなサブクラスがあり、それは畳み込み学習器（畳み込みニューラルネットワークを作成するもの）です。

```python
learn = create_cnn(data, models.resnet34, metrics=error_rate)
```

For now, just know that to create a learner for a convolutional neural network, you just have to tell it two things:
`data`: What's your data. Not surprisingly, it takes a data bunch.
`arch`: What's your architecture. There are lots of different ways of constructing a convolutional neural network. 

今のところ、畳み込みニューラルネットワークのLeanerを作成するには、次の2つを説明する必要があります。
`data`：このデータは何か。 当然のことながら、これはデータの集合です。
`arch`：このアーキテクチャはか。畳み込みニューラルネットワークを構築する方法はたくさんあります。

For now, the most important thing for you to know is that there's a particular kind of model called ResNet which works extremely well nearly all the time. For a while, at least, you really only need to be doing choosing between two things which is what size ResNet do you want. There are ResNet34 and ResNet50. When we are getting started with something, I'll pick a smaller one because it'll train faster. That's as much as you need to know to be a pretty good practitioner about architecture for now which is that there are two variants of one architecture that work pretty well: ResNet34 and ResNet50. Start with a smaller one and see if it's good enough.

今のところ、知っておくべき最も重要なことはResNetと呼ばれる特別な種類のモデルがあるということです。 しばらくの間、少なくとも、あなたはResNetの2つのサイズのどちらかを選択しなければいけないということです。 ResNet34とResNet50があります。 私たちが何かを開始するときは、私はより早く訓練ができる小さいほうを選択します。一つのアーキテクチャに２つの変種：ResNet34とResNet50があることを知っておくのは、いい専門家になるために必要です。小さいものから試してみて、それで十分かどうかを確認してください。

That is all the information we need to create a convolutional neural network learner. 

これが畳み込みニューラルネットワーク学習器を作成するために必要なすべての情報です。

There is one other thing I'm going to give it though which is a list of metrics. Metrics are literally just things that gets printed out as it's training. So I'm saying I would like you to print out error rate. 

もう一つ教えておきたいのがあります、それはメトリクスのリストです。メトリクスは文字通り訓練中のことを表示するものです。なので私はエラー率をプリントしてほしいと言っています。

[[37:25](https://youtu.be/BWWm4AzsdLk?t=2245)]

![](lesson1/c1.png)

The first time I run this on a newly installed box, it downloads the ResNet34 pre-trained weights. What that means is that this particular model has actually already been trained for a particular task. And that particular task is that it was trained on looking at about one and a half million pictures of all kinds of different things, a thousand categories of things, using an image dataset called ImageNet. So we can download those pre-trained weights so that we don't start with a model that knows nothing about anything, but we actually start with a model that knows how to recognize a thousand categories of things in ImageNet. I don't think all of these 37 categories of pet are in ImageNet but there were certainly some kinds of dog and some kinds of cat. So this pre-trained model knows quite a little bit about what pets look like, and it certainly knows quite a lot about what animals look like and what photos look like. So the idea is that we don't start with a model that knows nothing at all, but we start by downloading a model that knows something about recognizing images already. So it downloads for us automatically, the first time we use it, a pre-trained model and then from now on, it won't need to download it again - it'll just use the one we've got. 

新しい環境で初めてこれを実行するとき、これはResNet34の事前訓練済みの重みをダウンロードします。これの意味は、この特定のモデルが実際にすでに特定のタスクに対して訓練されているということです。この特定のタスクとは、ImageNetと呼ばれる画像データセットを使用して、様々な千種類・約150万枚の写真も用いて訓練されたことです。だから私たちは何も訓練されていないモデルから開始しないように事前訓練済みの重みをダウンロードすることができますが、しかし実際にはImageNetによって1000種類の物体を認識できるモデルから始めることになるのです。今回37種類のペットのすべてがImageNetにあるわけではないでしょうが、ある種の犬猫はいました。だからこの事前訓練されたモデルは、写真上でペットや動物がどのように見えるのかについてかなり多くのことをしっています。つまり、まったく何も知らないモデルから始めるのではなく、既に画像認識について何らかのことを知っているモデルをダウンロードすることから始めるのです。そのため、初回のみ事前訓練済みのモデルが自動的にダウンロードされ、それ以降は再びダウンロードすることはありません、入手済みのものだけを使用します。

## Transfer learning [[38:54](https://youtu.be/BWWm4AzsdLk?t=2334)]
転移学習

This is really important. We are going to learn a lot about this. It's kind of the focus of the whole course which is how to do this thing called "transfer learning." How to take a model that already knows how to do something pretty well and make it so that it can do your thing really well. We will take a pre-trained model, and then we fit it so that instead of predicting a thousand categories of ImageNet with ImageNet data, it predicts the 37 categories of pets using your pet data. By doing this, you can train models in 1/100 or less of the time of regular model training with 1/100 or less of the data of regular model training. Potentially, many thousands of times less. Remember I showed you the slide of Nikhil's lesson 1 project from last year? He used 30 images. There are not cricket and baseball images in ImageNet but it turns out that ImageNet is already so good at recognizing things in the world that just 30 examples of people playing baseball and cricket was enough to build a nearly perfect classifier. 

これは重要なことです。これについて多くを学習するでしょう。コース全体の焦点は「転移学習」と呼ばれる手法をどのように行うかにあります。なにかを上手くやる方法を知っているモデルをどうやって作るのか、あなたが自分のことを上手くやるように。私達は事前訓練済みのモデルを使い、ImageNetデータを千種類のカテゴリに当てはめるように、あなたのペットデータを使って37種類のカテゴリを予測します。こうすることで、通常のモデル訓練の1/100以下のデータで、通常のモデル訓練の1/100以下の時間でモデルを訓練することができます。何千倍もの時間の差がある。去年のレッスン1のNikhilのプロジェクトのスライドを覚えていますか？彼は30枚の画像を利用しました。 ImageNetにはクリケットと野球の画像はありませんでしたが、ImageNetはすでに世界のものに対して非常に優れた認識力があるので、野球とクリケットをしている人たちの30個の例だけでほぼ完璧な識別器を作成できます。

## Overfitting [[40:05](https://youtu.be/BWWm4AzsdLk?t=2405)]
過学習
Wait a minute, how do you know it can actually recognize pictures of people playing cricket versus baseball in general? Maybe it just learnt to recognize those 30. Maybe it's just cheating. That's called "overfitting". We'll be talking a lot about that during this course. But overfitting is where you don't learn to recognize pictures of say cricket versus baseball, but just these particular cricketers in these particular photos and these particular baseball players in these particular photos. We have to make sure that we don't overfit. The way to do that is using something called a validation set. A validation set is a set of images that your model does not get to look at. So these metrics (e.g. error_rate) get printed out automatically using the validation set - a set of images that our model never got to see.  When we created our data bunch, it automatically created a validation set for us. We'll learn lots of ways of creating and using validation sets, but because we're trying to bake in all of the best practices, we actually make it nearly impossible for you not to use a validation set. Because if you're not using a validation set, you don't know if you're overfitting. So we always print out the metrics on a validation, we've always hold it out, we always make sure that the model doesn't touch it. That's all done for you, and all built into this data bunch object.

ちょっと待ってください、それが実際に一般的にクリケットや野球をしている人々の写真を認識できているとどうやって知るのですか？もしかしたらそれはその３０枚の画像を認識することのみを学んだだけなのかもしれない。それはずるい。これを「過学習」と呼びます。これについてはコースの中でたくさん話すことになるでしょう。しかし過学習は、クリケットと野球の写真を認識することを学ぶのではなく、写真の中から特定のクリケット選手の野球選手を学んでしまいます。過学習しないようにする必要があります。それは評価セットと呼ばれるものを使うことです。評価セットとは、モデルが見ることのできない画像のセットです。そのため、これらのメトリクス（エラー率など）は、検証セット - モデルが見ることができない一連の画像を使用して自動的に表示されます。データ集合を作成するとき、自動的に検証セットも作成されます。たくさんの検証セットの作成・使用方法について学んでいきますが、しかしベストプラクティスに従うため、検証セットを使用せずにいようとすることはほぼ不可能でしょう。なぜならもし検証セットを使わないのならば、あなたが過学習を知ることはできないからです。私達はいつも検証結果の測定値を表示し、私達がそれを行うためにいつもモデルにはそれに触れないようにします。これですべて完了しました、作成済みのものはすべてデータオブジェクトに組み込まれました。

## Fitting your model [[41:40](https://youtu.be/BWWm4AzsdLk?t=2500)]
モデルへの適合
So now we have a ConvLearner, we can fit it. You can just use a method called `fit` but in practice, you should nearly always use a method called `fit_one_cycle`. In short, one cycle learning is [a paper](https://arxiv.org/pdf/1803.09820.pdf) that was released in April and turned out to be dramatically better both more accurate and faster than any previous approach. Again, I don't want to teach you how to do 2017 deep learning. In 2018, the best way to fit models is to use something called one cycle. 

これで畳み込み学習器が完成です。`fit`と呼ばれるメソッドを使うことができますが、実際にはほぼ常に` fit_one_cycle`と呼ばれるメソッドを使ってください。 簡単に言うと、1サイクル学習は（2018年)4月にリリースされた[論文]（https://arxiv.org/pdf/1803.09820.pdf） であり、過去どの手法よりも劇的に正確かつ高速であることが判明しました。 繰り返しますが、2017年のディープラーニングの方法をあなたに教えたくはありません。 2018年では、モデルに適合させる最も良い手法は1サイクルと呼ばれるものを使うことです。

For now, just know that this number, 4, basically decides how many times do we go through the entire dataset, how many times do we show the dataset to the model so that it can learn from it. Each time it sees a picture, it's going to get a little bit better. But it's going to take time and it means it could overfit. If it sees the same picture too many times, it will just learn to recognize that picture, not pets in general. We'll learn all about how to tune this number during the next couple of lessons but starting out with 4 is a pretty good start just to see how it goes and you can actually see after four epochs or four cycles, we got an error rate of 6%. And it took 1 minute and 56 seconds. 

今のところ、この4という数字は基本的に、データセット全体を何回学習するか、データセットをモデルにモデルに何回見せて学習できるようにするかを決定します。 画像を見るたびに、少しずつ結果は良くなります。 しかし、それは時間がかかるし過学習する可能性があることを意味します。 同じ画像を何度も見すぎると、一般的にはペットではなくその画像そのものを認識するようになります。次回、次次回の講義でこの数を調整する方法を学びますが、ひとまず4から始めることは、4エポックまたは4サイクル後にそれがどうなるかを確認するための良いスタートです。エラー率は6％で、1分56秒かかりました。

```python
learn.fit_one_cycle(4)
```

```
Total time: 01:10
epoch  train loss  valid loss  error_rate
1      1.175709    0.318438    0.099800    (00:18)
2      0.492309    0.229078    0.075183    (00:17)
3      0.336315    0.211106    0.067199    (00:17)
4      0.233666    0.191813    0.057219    (00:17)
```
So 94% of the time, we correctly picked the exact right one of those 37 dog and cat breeds which feels pretty good to me. But to get a sense of how good it is, maybe we should go back and look at the paper. Remember, I said the nice thing about using academic papers or Kaggle dataset is we can compare our solution to whatever the best people in Kaggle did or in the academics did. This particular dataset of pet breeds is from 2012 and if I scroll through the paper, you'll generally find in any academic paper there'll be a section called experiments about 2/3 of the way through. If you find a section on experiments, then you can find a section on accuracy and they've got lots of different models and their models. The models as you'll read about in the paper, it's really pet specific. They learn something about how pet heads look and how pet bodies look, and pet image in general look. And they combine them all together and once they use all of this complex code and math, they got an accuracy of 59%. So in 2012, this highly pet specific analysis got an accuracy of 59%. These were the top researchers from Oxford University. Today in 2018, with basically about three lines of code, we got 94% (i.e. 6% error). So that gives you a sense of how far we've come with deep learning, and particularly with PyTorch and fastai, how easy things are.

94％の割合で37種類の犬と猫のを正しく分類できたので、これは一見良い結果のように感じられます。しかしそれがどれほど優れているかを把握するためには、おそらく論文に戻って見るべきでしょう。覚えておいてください、私は学術論文やKaggleデータセットを使用することの利点として、Kaggleの優秀な人や学者の間で行われたことと比較できることだと言いました。このペットの品種に関するデータセットは2012年からのものです。この論文を確認すると、一般的にどの学術論文にも2/3程度を実験という章が締めています。実験に関する章がある場合には、精度に関する章も見つけることができ、それらにはさまざまなモデルと彼らのモデルがあります。あなたがその論文で読んでいるモデルはペット特有のものです。ペットの頭や体、一般的な見え方について学ばせています。そしてそれらをすべて組み合わせた複雑なコードで59％の精度だったのです。その結果2012年にはペット特有の識別手法で59％の精度に到達したのです。これらはオックスフォード大学のトップ研究者のものでした。今日の2018年には、基本的に約3行のコードで、私たちは94％の精度（すなわち6％のエラー率）を得ました。これによって私達はディープラーニングによってどこまで遠くまで来たのか、そして特にPyTorchとfastaiがどれほど簡単であるかの実感を与えてくれます。

[[46:43](https://youtu.be/BWWm4AzsdLk?t=2803)]
We just trained a model. We don't know exactly what that involved or how it happened but we do know that with 3 or 4 lines of code, we've built something which smashed the accuracy of the state-of-the-art of 2012. 6% error certainly sounds like pretty impressive for something that can recognize different dog breeds and cat breeds, but we don't really know why it work, but we will. That's okay.

モデルを訓練しました。 これに何が含まれていてどんなことが起こったのかは正確にはわかりませんが、しかし3,4行のコードで2012年の最先端の精度を破るほどのものを構築できたことを知っています。6%のエラーというとたしかに異なる犬と猫の品種を認識できている印象を与えてくれますが、それがなぜ上手く行くのかはわかります。けれどあとでわかるようになります、大丈夫。

### The number one regret of past students:
過去の学生の一番の後悔：

![](lesson1/102.png)



> ### **So please run the code. Really run the code.** [[47:54](https://youtu.be/BWWm4AzsdLk?t=2874)]
お願いだからコードは実行してください。本当に実行してください

Your most important skills to practice are learning and understanding what goes in and what comes out. 
実践で最も大事なスキルは何が起きて何が出てくるのかを学び理解することです。

![](lesson1/103.png)

Fastai library is pretty new, but it's getting an extraordinary amount of traction. It's making a lot of things a lot easier, but it's also making new things possible. So really understanding the fastai software is something which is going to take you a long way. And the best way to really understand the fastai software well is by using the [fastai documentation](http://docs.fast.ai/).

Fastaiライブラリはとても新しいものですが、驚くほどの勢いで成長しています。これによってたくさんのことが簡単になりますが、またそれにより新しいことが可能になります。真にfastaiライブラリを理解するには長い道のりを行くことになるでしょう。fastaiのソフトウェアを本当に深く理解するために最も適切な方法は[fastaiドキュメント]（http://docs.fast.ai/） を読むことです。

### Keras[ [49:25](https://youtu.be/BWWm4AzsdLk?t=2965)]

![](lesson1/105.png)

So how does it compare? There's only one major other piece of software like fastai that tries to make deep learning easy to use and that's Keras. Keras is a really terrific piece of software, we actually used it for the previous courses until we switch to fastai. It runs on top of Tensorflow. It was the gold standard for making deep learning easy to use before. But life is much easier with fastai. So if you look at the last year's course exercise which is getting dogs vs. cats, fastai lets you get much more accurate (less than half the error on a validation set), training time is less than half the time, lines of code is about 1/6. The lines of code are more important than you might realize because those 31 lines of Keras code involved you making a lot of decisions, setting lots of parameters, doing lots of configuration. So that's all stuff where you have to know how to set those things to get best practice results. Or else, those 5 lines of code, any time we know what to do for you, we do it for you. Anytime we can pick a good default, we pick it for you. So hopefully you will find this a really useful library, not just for learning deep learning but for taking it a very long way.

これはどのような比較ですか？fastaiのようにディープラーニングを簡単に使えるようにしようとするソフトウェアは他に1つだけあります。それがKerasです。 Kerasはとても素晴らしいソフトウェアで、fastaiができるまでは以前のこのコースでも使用していました。これはTensorflow上で実行します。以前までディープラーニングを簡単に使うための王道の方法でした。しかし、人生はfastaiの方がずっと簡単です。犬対猫の昨年のコース演習では、fastaiはもっと正確でした（評価セットのエラー率は半分以下）、トレーニング時間は半分以下、コード行は約1/6。 31行のKerasコードでは、多くのことを決め、多数のパラメータを調整し、多数の設定する必要があるため、コード行数はあなたが考えるよりももっと重要なことです。そして、ベストな結果を得るために知る必要のある設定はこれだけです。それ以外のこの5行のコードは、私達はあなたのために何をすべきかいつでも知っているし、それを実行します。良いデフォルト設定が選べるときはいつでもあなたのためにそれを選択します。ディープラーニングのために長い道のりを歩む必要がないのよう、あなたが本当に便利なライブラリに出会えることを願います。


[[50:53](https://youtu.be/BWWm4AzsdLk?t=3053)]

![](lesson1/106.png)



How far can you take it? All of the research that we do at fastai uses the library and an example of the research we did which was recently featured in Wired describes a new breakthrough in a natural language processing which people are calling the ImageNet moment which is basically we broke a new state-of-the-art result in text classification which OpenAI then built on top of our paper with more computing, more data to do different tasks to take it even further. This is an example of something we've done in the last 6 months in conjunction with my colleague Sebastian Ruder - an example of something that's being built in the fastai library and you are going to learn how to use this brand new model in three lessons time. You're actually going to get this exact result from this exact paper yourself.

どのくらい先にまで行けますか？fastaiで行っているすべての研究はこのライブラリを使用しており、例えば最近Wiredで取り上げられた研究では、ImageNetと呼ばれる自然言語処理で、OpenAIによる私達の論文よりはるかに多くのコンピュータ・データ・異なるタスクによるテキスト分類の記録を破るブレークスルーを起こしました。これは私の同僚であるSebastian Ruderと共に最近6ヶ月間で実施したことの例です -  fastaiライブラリにいくつか用意されｔものの中の一つの例を使い、これから三回の講義であなたはこの新しいモデルの使い方を学びます。この緻密な論文から緻密な結果を得ることができるでしょう。

[[51:50](https://youtu.be/BWWm4AzsdLk?t=3110)]
![](lesson1/107.png)
Another example, one of our alumni, Hamel Husain built a new system for natural language semantic code search, you can find it on Github where you can actually type in English sentences and find snippets of code that do the thing you asked for. Again, it's being built with the fastai library using the techniques you'll learn in the next seven weeks.

別の例では、卒業生の一人であるHamel Husainが新しい自然言語意味コード検索システムを構築しました。Githubで公開されています。 繰り返しますが、これから７週間の講義で習得する手法を使った、fastaiライブラリを利用して構築されています。


[[52:27](https://youtu.be/BWWm4AzsdLk?t=3147)]

The best place to learn about these things and get involved in these things is on the forums where as well as categories for each part of the course and there is also a general category for deep learning where people talk about research papers applications. 

講義について学び参加するのに最適な場所はフォーラムです、各コースのカテゴリーだけでなく一般的なディープラーニングの研究論文の応用について話す場所もあります。

Even though today, we are focusing on a small number of lines of code to a particular thing which is image classification and we are not learning much math or theory, over these seven weeks and then part two, we are going to go deeper and deeper. 

今日、私たちは特に画像識別と呼ばれる分野の少数のコードに焦点をおいていおり、数学や理論については深く学びません、これからの７週間やパート2のコースで、より深く深く学んで行きます。

### Where can that take you? [[53:05](https://youtu.be/BWWm4AzsdLk?t=3185)]
どこまで行けるか？

![](lesson1/108.png)

This is Sarah Hooker. She did our first course a couple of years ago. She started learning to code two years before she took our course. She started a nonprofit called Delta Analytics, they helped build this amazing system where they attached old mobile phones to trees in Kanyan rain forests and used it to listen for chainsaw noises, and then they used deep learning to figure out when there was a chainsaw being used and then they had a system setup to alert rangers to go out and stop illegal deforestation in the rainforests. That was something she was doing while she was in the course as part of her class projects. 

彼女はSarah Hooker。 数年前にこのコースの最初のバージョンを受講しました。彼女はこの講座を受講する二年前にプログラミングの勉強を始めました。 彼女はDelta Analyticsと呼ばれる非営利団体を作り、古い携帯電話をKanyanの熱帯雨林の木々に取り付けてチェーンソーの音を検知する素晴らしいシステムを作り、彼女らが活用したディープラーニングはチェーンソーの存在を検知し、レンジャーにアラートを発信して熱帯雨林の違法な森林伐採を阻止しました。それは彼女がクラスのプロジェクトの一部としてコースを受講している間に行ったことでした。

![](lesson1/109.png)
She is now a Google Brain researcher, publishing some papers, and now she is going to Africa to set up a Google Brain's first deep learning research center in Africa. She worked her arse off. She really really invested in this course. Not just doing all of the assignments but also going out and reading Ian Goodfellow's book, and doing lots of other things. It really shows where somebody who has no computer science or math background at all can be now one of the world's top deep learning researchers and doing very valuable work.

彼女は現在Google Brainの研究者で、何本か論文も発表しています。今、彼女はアフリカにGoogle Brain最初のディープラーニング研究所を設立するためにアフリカに行く予定です。 彼女はとても懸命に働いた。 彼女は本当に本当にこのコースに本当に労力を費やしました。 すべての課題をこなすだけでなく、外に出てIan Goodfellowの本を読み、そしてその他たくさんのことを行いました。 これはコンピュータサイエンスや数学の知識をまったく持たない人が、世界クラスのトップディープラーニング研究者の一人になり、非常に貴重な仕事をできることを示しています。

[[54:49](https://youtu.be/BWWm4AzsdLk?t=3289)]

![](lesson1/110.png)



Another example from our most recent course, Christine Payne. She is now at OpenAI and you can find [her post](http://christinemcleavey.com/clara-a-neural-net-music-generator/) and actually listen to her music samples of something she built to automatically create chamber music compositions. 

最も最近のコースの受講者、Christine Payneの例です。 彼女は現在OpenAIにいます、[彼女の投稿]（http://christinemcleavey.com/clara-a-neural-net-music-generator/） を見て、自動的に生成された室内楽の音楽のサンプルを聞くことができます。

![](lesson1/111.png)

She is a classical pianist. Now I will say she is not your average classical pianist. She's a classical pianist who also has a master's in medical research in Stanford, and studied neuroscience, and was a high-performance computing expert at DE Shaw, Co-Valedictorian at Princeton. Anyway. Very annoying person, good at everything she does. But I think it's really cool to see how a domain expert of playing piano can go through the fastai course and come out the other end as OpenAI fellow. 

彼女はクラシックピアニストです。 しかし彼女は平均的なクラシックピアニストではありません。 彼女はスタンフォード大学で医学研究の修士号を持ち、神経科学を学び、DE Shawの高性能コンピューティングの専門家で、プリンストンの共同卒業生代表でした とにかくすさまじい人、彼女はすべてのことが得意です。 しかし、ピアノを弾くことが専門な専門家がどのようにfastaiコースを終了し、OpenAIフェローとして旅立てることは本当に素晴らしいと思います。

Interestingly, one of our other alumni of the course recently interviewed her for a blog post series he is doing on top AI researchers and she said one of the most important pieces of advice she got was from me and she said the advice was:

興味深いことに、コースの他の卒業生の一人は最近彼がトップのAI研究者関するブログ記事シリーズのために彼女にインタビューしました。そして彼女はこれまで得たアドバイスの最も重要なものの1つが私からだったと述べました。

> #### Pick one project. Do it really well. Make it fantastic. [56:20](https://youtu.be/BWWm4AzsdLk?t=3380)
プロジェクトを決め、とても上手にこなし、素晴らしいものにしなさい


We're going to be talking a lot about you doing projects and making them fantastic during this course.

このコースでは、皆さんがプロジェクトを実行して素晴らしいものにすることについて多くを語ります。

[[56:36](https://youtu.be/BWWm4AzsdLk?t=3396)]
Having said that, I don't really want you to go to AI or Google Brain. What I really want you to do is to go back to your workplace or your passion project and apply these skills there. 

とは言え、私はあなたにOpenAIやGoogle Brainに行ってほしいわけではないのです。 私が本当にしてほしいことは、あなたの職場やあなたの情熱を燃やすプロジェクトに戻り、そこでこのスキルを発揮することです。

![](lesson1/112.png)
MIT released a deep learning course and they highlighted in their announcement this medical imaging example. One of our students Alex who is a radiologist said you guys just showed a model overfitting. I can tell because I am a radiologist and this is not what this would look like on a chest film. This is what it should look like and as a deep learning practitioner, this is how I know this is what happened in your model. So Alex is combining his knowledge of radiology and his knowledge of deep learning to assess MIT's model from just two images very accurately. So this is actually what I want most of you to be doing is to take your domain expertise and combine it with the deep learning practical aspects you'll learn in this course and bring them together like Alex is doing here. So a lot of radiologists have actually gone through this course now and have built journal clubs and American Council of Radiology practice groups. There's a data science institute at the ACR now and Alex is one of the people who is providing a lot of leadership in this area. And I would love you to do the same kind of thing that Alex is doing which is to really bring deep learning leadership into your industry and to your social impact project, whatever it is that you are trying to do. 

MITはディープラーニングコースを発表し、その中でこの医療用画像処理の例を強調しました。放射線科医であるこのコースの生徒Alexはみんなにこのモデルは過学習であると言いました。私は放射線科医で、これが胸部画像のように見えないのでそう言うことが言えると。これはディープラーニングの専門家として、モデルに何が起こったかを知る方法を示しています。なので、Alexは自分の放射線学の知識とディープラーニングの知識を組み合わせて、2つの画像からMITのモデルを非常に正確に評価しました。ですから、私が実際にみなさんにしてほしいことは、みなさんの専門知識を組み合わせてディープラーニングの実践的な面を組み合わせることです。そして、多くの放射線科医が実際にこのコースを受講し、ジャーナルクラブとアメリカ癌放射線学（ACR）の実践グループを設立しました。現在ACRにはデータサイエンス研究所があり、Alexはこの分野で多大なリーダーシップを発揮している1人です。そして、みなさんにもAlexと同じようなことをやってほしいと願っています。それはあなたがやろうとしていることであっても、本当にあなたの業界とあなたの社会的に影響を与えるプロジェクトにディープラーニングへのリーダーシップをもたらします。

[[58:22](https://youtu.be/BWWm4AzsdLk?t=3502)]

![](lesson1/113.png)

Another great example. This is Melissa Fabros who is a English literature PhD who studied gendered language in English literature or something and actually Rachel at the previous job taught her to code. Then she came to the fastai course. She helped Kiva, a micro lending a social impact organization, to build a system that can recognize faces. Why is that necessary? We're going to be talking a lot about this but because most AI researchers are white men, most computer vision software can only recognize white male faces effectively. In fast, I think it was IBM system was like 99.8% accurate on common white face men versus 65% accurate on dark skinned women. So it's like 30 or 40 times worse for black women versus white men. This is really important because for Kiva, black women perhaps are the most common user base for their micro lending platform. So Melissa after taking our course, again working her arse off, and being super intense in her study and her work won this $1,000,000 AI challenge for her work for Kiva. 

もう一つの素晴らしい例です。彼女はMelissa Fabros、英文学などでジェンダー言語を研究した英文学博士で、以前の職場でレイチェルがプログラミングを教えていました。それから彼女はfastaiコースに来ました。彼女は、社会的影響力のある組織であるマイクロ融資のKivaで、顔認識システムを構築するのを助けました。なぜそれが必要なのか。私たちはこのことについて多く話しているつもりですが、ほとんどのAI研究者は白人男性なので、ほとんどの画像認識顔ソフトは白人男性の顔しか的確に認識できません。簡単に言えば、IBMのシステムは一般的な白い肌の男性で99.8％の正確な認識率であるのに対し、浅黒い肌の女性では65％の正確さの認識率だったと思います。だから、黒人女性は白人男性の30〜40倍も悪いのです。これは本当に重要です。なぜならKivaにとって、黒人女性はおそらく彼らのマイクロ融資プラットフォームの最も一般的なユーザー層だからです。それでMelissaはこのコースを受講し、再び懸命に働き、この研究に熱心に取り組み、彼女の研究はAIチャレンジで彼女のLivaでの仕事の結果で１００万ドルを勝ち取りました。

[[59:53](https://youtu.be/BWWm4AzsdLk?t=3593)]

![](lesson1/114.png)

Karthik did our course and realized that the thing he wanted to do wasn't at his company. It was something else which is to help blind people to understand the world around them. So he started a new startup called envision. You can download the app and point your phone to things and it will tell you what it sees. I actually talked to a blind lady about these kinds of apps the other day and she confirmed to me this is a super useful thing for visually disabled users.  

Karthikは私たちのコースを受講し、彼がやりたかったことは彼の会社にはないことに気づきました。 それは盲目の人々が周りの世界を理解するのを補助する他の何かでした。 なので彼はenvisionという新しいスタートアップを立ち上げました。 あなたはアプリをダウンロードして周りの物にスマートフォンを向けると、その物体がなにか教えてくれるでしょう。 私は先日こういったアプリについて実際に盲目の女性と会話し、彼女はこれが視覚障害者にとって非常に役に立つものであることを確認しました。


[[1:00:24](https://youtu.be/BWWm4AzsdLk?t=3624)]
![](lesson1/115.png)

The level that you can get to, with the content that you're going to get over these seven weeks and with this software can get you right to the cutting edge in areas you might find surprising. I helped a team of some of our students and some collaborators on actually breaking the world record for how quickly you can train ImageNet. We used standard AWS cloud infrastructure, cost of $40 of compute to train this model using fastai library, the technique you learn in this course. So it can really take you a long way. So don't be put off by this what might seem pretty simple at first. We are going deeper and deeper.

あなたがこれからの７週間で学ぶコンテンツとソフトウェアで到達可能なレベルは、驚くほどの最先端のものになるでしょう。私は何人かの学生と共同研究者のチームが、ImageNetをどれだけ早く訓練できるかの世界記録を破ることを助けました。我々はAWSのクラウド設備を使い、40$の料金のコンピュータでfastaiライブラリを使ってこのコースであなたが学ぶ手法でモデルを訓練しました。だからあなたは本当に長い道をゆくことができます。なので、最初は単純に見えるようなことも先延ばしにしないでください。私達は深く深く行きます。

[[1:01:17](https://youtu.be/BWWm4AzsdLk?t=3677)]
![](lesson1/116.png)

You can also use it for other kinds of passion project. Helena Sarin - you should definitely check out her Twitter account [@glagolista](https://twitter.com/glagolista). This art is basically a new style of art that she's developed which combines her painting and drawing with generative adversarial models to create these extraordinary results. I think this is super cool. She is not a professional artists, she is a professional software developer but she keeps on producing these beautiful results. When she started, her art had not really been shown or discussed anywhere, now there's recently been some quite high profile article describing how she is creating a new form of art. 

これは他の種類の情熱をかけるプロジェクトにも活用できます。Helena Sarin  - あなたは必ず彼女のTwitterアカウントをチェックすべきです。これは彼女が開発した新しいスタイルの芸術で、彼女が書いた絵と敵対的生成モデルを組み合わせて素晴らしい作品を作り出しています。これはとてもクールだと思います。彼女はプロのアーティストではなく、彼女はプロのソフトウェア開発者ですが、このような素晴らしい結果を生み出し続けています。彼女がこれを始めたとき、彼女の芸術は実際にはどこに対しても見せられたり議論されたりはしていませんでした。近頃では、彼女が新しい形式の芸術をどのように生み出すのかに注目した記事がいくつもあります。

![](lesson1/117.png)

Equally important, Brad Kenstler who figured out how to make a picture of Kanye out of pictures of Patrick Stewart's head. Also something you will learn to do if you wish to. This particular type of what's called "style transfer" - it's a really interesting tweak that allowed him to do something that hadn't quite been done before. This particular picture helped him to get a job as a deep learning specialist at AWS.

同じくらい重要なものとして、Patrick Stewartの頭の絵からKanyeの絵を作り出したBrad Kenstlerです。あなたが同じようなことをしたいならやがて学ぶであろう内容です。この特定の手法は”スタイル転送”と呼ばれるものです。 - これは以前ならできなかったことができるようになる本当に面白い微調整です。この絵は彼がAWSのディープラーニングスペシャリストとしての職を得ることを助けました。

[[1:02:41](https://youtu.be/BWWm4AzsdLk?t=3761)]

Another alumni actually worked at Splunk as a software engineer and he designed an algorithm which basically turned Splunk to be fantastically good at identifying fraud and we'll talk more about it shortly. 

ある他の卒業生はソフトウェアエンジニアとしてSplunkで働いていおり、彼はSplunkが詐欺を識別することを素晴らしく向上させるアルゴリズムを設計しました、これについてはすぐあとにもっと話します。

![](lesson1/118.png)

If you've seen Silicon Valley, the HBO series, the hotdog Not Hotdog app - that's actually a real app you can download and it was built by Tim Anglade as a fastai student project. So there's a lot of cool stuff that you can do. It was Emmy nominated. We only have one Emmy nominated fastai alumni at this stage, so please help change that.

もしシリコンバレーでHBOシリーズ、ホットドッグアプリではないホットドッグを見たことがあるならば - これはTim Angladeがfastaiの学生プロジェクトで作成した実際にダウンロードできるアプリです。だからあなたができることはたくさんあります。これはエミー賞にノミネートされました。そんなfasiaiの卒業生は今のところこの人だけですので、あなたがこれを変える手助けをしてください。

![](lesson1/119.png)
[[1:03:30](https://youtu.be/BWWm4AzsdLk?t=3810)]

The other thing, the forum thread can turn into these really cool things. So Francisco was a really boring McKinsey consultant like me. So Francisco and I both have this shameful past that we were McKinsey consultants, but we left and we're okay now. He started this thread saying like this stuff we've just been learning about building NLP in different languages, let's try and do lots of different languages, and he started this thing called the language model zoo and out of that, there's now been an academic competition was won in Polish that led to an academic paper, Thai state of the art, German state of the art, basically as students have been coming up with new state of the art results across lots of different languages and this all is entirely done by students working together through the forum. 

もうひとつ、フォーラムのスレッドは本当にクールなものになります。Franciscoは私のような本当につまらないMcKinseyのコンサルタントでした。なのでFeanciscoと私はMcKinseyのコンサルトであった苦い過去があります。でももうそこから去りましたので大丈夫です。彼はこのスレッドのようにNLPを様々な言語に構築する方法を勉強しています。ぜひたくさんの言語で試してみましょう。彼が始めたこれはZooという言語モデルで、この学術論文はポーランドでの学術コンテストで勝利し、タイ語やドイツ度でも最先端の結果を出し、基本的に学生が様々な結果で最先端の結果を出しており、これらは基本的にこのフォーラムでを通じて学生が共同作業することで達成されました。

So please get on the forum. But don't be intimidated because everybody you see on the forum, the vast majority of posting post all the darn time. They've been doing this a lot and they do it a lot of the time. So at first, it can feel intimidating because it can feel like you're the only new person there. But you're not. You're all new people, so when you just get out there and say like "okay all you people getting these state of the art results in German language modeling, I can't start my server, I try to click the notebook and I get an error, what do I do?" People will help you. Just make sure you provide all the information ([how to ask for help](https://forums.fast.ai/t/how-to-ask-for-help/10421)). 

なので、ぜひフォーラムに参加してください。フォーラムにいるすべての人たちは圧倒的な時間を費やしているように見えるかもしれないけれども、怖がらないでください。か彼らは多くそれをやってきて多くの時間を費やしました。そのために最初はあなただけが新しく始めた唯一の人のように感じるので、威圧的なものを感じるでしょう。しかしあなたは違います。あなたは新しい人です。あなたがそこに参加して「ねえ、最先端の結果が得られるドイツ語モデルが自分のサーバーで動かないんだけど、Notebookをクリックしてみたらエラーが出たんだ、どうすればいい？」と聞いてみましょう。みんながあなたを助けるでしょう。あなたが得たすべての情報を提供してください。

Or if you've got something to add! If people are talking about crop yield analysis and you're a farmer and you think oh I've got something to add, please mention it even if you are not sure it's exactly relevant. It's fine. Just get involved. Because remember, everybody else in the forum started out also intimidated. We all start out not knowing things. So just get out there and try it!

もし追加するものがあるならば！もし皆が作物の収穫量の分析が話しており、もしあなたが農家で、そのことについて追加のことが言えるのなら、ぜひそれが確かに関連しているかどうかわからなくても発言してください。それは良いことです。ただ参加してください。覚えておいてください、他のみんなも怯えながらフォーラムを始めました。みな最初は何も知らないのです。なのでこの場に参加して試してみましょう！

[[1:05:59](https://youtu.be/BWWm4AzsdLk?t=3959)]
**Question**: Why are we using ResNet as opposed to ?

InceptionではなくResNetを使用するのはなぜですか？

There are lots of architectures to choose from and it would be fair to say there isn't one best one but if you look at things like the Stanford DAWNBench benchmark of image classification, you'll see in first place, second place,  third place, and fourth place all use ResNet. ResNet is good enough, so it's fine. 
![](lesson1/120.png)

アーキテクチャの選択肢はいくつもあり、どれが一番良いというわけではないですが、Stanford DAWNBenchの画像分類ベンチマークを見ると、1位、2位、3位、4位はすべてResNetを使用しています。 ResNetは十分に優れているのでいいでしょう。

The main reason you might want a different architecture is if you want to do edge computing, so if you want to create a model that's going to sit on somebody's mobile phone. Having said that, even there, most of the time, I reckon the best way to get a model onto somebody's mobile phone is to run it on your server and then have your mobile phone app talk to it. It really makes life a lot easier and you get a lot more flexibility. But if you really do need to run something on a low powered device, then there are special architectures for that. So the particular question was about Inception. That's a particular another architecture which tends to be pretty memory intensive but it's okay. It's not terribly resilient. One of the things we try to show you is stuff which just tends to always work even if you don't quite tune everything perfectly. So ResNet tends to work pretty well across a wide range of different kind of details around choices that you might make. So I think it's pretty good.

異なるアーキテクチャが必要になる主な理由は、あなたがエッジコンピューティングで実行したい場合、言い換えると携帯電話に搭載するモデルを作成したい場合です。しかしほとんどの場合において、携帯電話にモデル搭載する一番の方法は、サーバー上で実行してから携帯電話のアプリにそれを表示させることです。これは本当に生活をより簡単にし、多くの柔軟性を得られる。しかしあなたが本当に低電力デバイス上で何かを実行する必要があるのであれば、そのための特別なアーキテクチャがあります。先の質問はInceptionについてでしたね。これはかなりメモリを消費する別のアーキテクチャですが、大丈夫。それほど復元力はありません。あなたに見せたいことの1つは、すべてを完璧に調整しなくてもだいたいうまくいって十分だということです。なのでResNetはあなたがやりたいと選択したいろいろな種類のものに対して細部にわたってかなりうまくいく傾向があります。だからこれはとてもいいと思います。

[[1:07:58](https://youtu.be/BWWm4AzsdLk?t=4078)]

We've got this trained model and what's actually happened as we'll learn is it's basically creating a set of weights. If you've ever done anything like a linear regression or logistic regression, you'll be familiar with coefficients. We basically found some coefficients and parameters that work pretty well and it took us a minute and 56 seconds. So if we want to start doing some more playing around and come back later, we probably should save those weights. You can just go `learn.save` and give it a name. It's going to put it in a model subdirectory in the same place the data came from, so if you save different models or different data bunches from different datasets, they'll all be kept separate. So don't worry about it.

私達にはこの訓練されたモデルがあり、これから学ぶときにやることは基本的に重みのセットを作成することです。もしあなたに線形回帰またはロジスティック回帰の経験があるなら、係数のことをよく知っているでしょう。私達は基本的にかなり上手く動く複数の係数とパラメータを見つけ、これは1分56秒かかりました。もしもう少しいろいろやってから戻ってくるなら、その重みを保存したほうがいい。 `learn.save`に移動して名前を付けるだけです。 データを取得したのと同じ場所のmodelのサブディレクトリに配置するので、異なるモデルや異なるデータセットを異なるデータセットから保存した場合、これらはすべて別々に保存されます。 なので心配し無用です。

```python
learn.save('stage-1')
```



## Results [[1:08:54](https://youtu.be/BWWm4AzsdLk?t=4134)]

To see what comes out, we could use this class for class interpretation. We are going to use this factory method from learner, so we pass in a learn object. Remember a learn object knows two things: 
1. What's your data
2. What is your model. Now it's not just an architecture, it's actually a trained model 

That's all the information we need to interpret that model. 

何が表示されるかを確認するために、クラスの実行のためにこのクラスを使うことができます。 学習器でこのファクトリメソッドを使用することになるので、学習用オブジェクトを渡します。 学習用オブジェクトについて2つのことを知り忘れないでください。
1.あなたのデータは何ですか
2.あなたのモデルは何ですか。 これは単なるアーキテクチャではなく、既に訓練済みのモデルです。

これがモデルの解釈に必要なすべての情報です。

```python
interp = ClassificationInterpretation.from_learner(learn)
```

One of the things, perhaps the most useful things to do is called plot_top_losses. We are going to be learning a lot about this idea of loss functions shortly but in short, a loss function is something that tells you how good was your prediction. Specifically that means if you predicted one class of cat with great confidence, but actually you were wrong, then that's going to have a high loss because you were very confident about the wrong answer. So that's what it basically means to have high loss. By plotting the top losses, we are going to find out what were the things that we were the most wrong on, or the most confident about what we got wrong. 

おそらくもっともやるべきことの一つはplot_top_lossesというものです。 このあとこの損失関数についてはたくさん学習しますが、要するに、損失関数とはあなたの予測がどれほど良かったか教えてくれるものです。具体的には、もしあるクラスの猫を自信を持って予測したが実際には間違っていた場合、間違った答え
に非常に自信を持っていたので、それだけ大きな損失になります。なのでこれは基本的に高い損失を持つことを意味しています。 最も高い損失のものをプロットすることで、私達は私達が最も悪かったもの、もしくは最も自信があったのに間違ったものは何かを見つけようとします。

```python
interp.plot_top_losses(9, figsize=(15,11))

```
![](lesson1/9.png)

It prints out four things. What do they mean? Perhaps we should look at the document.

これは4つのものを表示します。それはどういう意味か？ ドキュメントを確認すべきでしょう。

We have already seen `help`, and `help` just prints out a quick little summary. But if you want to really see how to do something use `doc`.

私たちはすでに `help`を見ましたが` help`は簡単な要約を出力するだけです。 もしあなたが本当に使い方を確認したいなら `doc`を使いましょう。

![](lesson1/121.png)



`doc` tells you the same information as `help` but it has this very important thing which is `Show in docs`. When you click on it, it pops up the documentation for that method or class or function or whatever:

`doc`は` help`と同じ情報を表示しますが、 `Show in docs`であることは非常に重要意味合いがあります。あなたがこれをクリックすると、そのメソッドやクラス・関数あるいはその他いろいろなドキュメントをポップアップします。

![](lesson1/122.png)

It starts out by showing us the same information about what are the parameters it takes a long with the doc string. But then tells you more information:

これはdoc文字列によって同じパラメータの情報を得るのに時間がかかることです。 しかしそのことであなたにもっと多くの情報を伝えます：

> The title of each image shows: prediction, actual, loss, probability of actual class.

>各画像のタイトルは次のとおりです。予測の値、実際の値、損失値、実際のクラスの可能性。

The documentation always has working code. This is your friend when you're trying to figure out how to use these things. The other thing I'll mention is if you're somewhat experienced Python programmer, you'll find the source code of fastai really easy to read. We are trying to write everything in just a small number (much less than half a screen) of code. If you click on `[source]` you can jump straight to the source code.

ドキュメントにはいつも動くコードがあります。これはあなたがどうやってこれらのものを使って実行すべきか試すときの友です。付け加えると、もしあなたがいくらかのPythonプログラマーの経験があるなら、fastaiのソースコードはとても読みやすいと感じるでしょう。 我々は数行の（画面半分よりもっとすくない）コードですべてを行おうとしています。 [source]をクリックすると、ソースコードに直接移動できます。

![](lesson1/123.png)

Here is plot_top_loss, and this is also a great way to find out how to use the fastai library. Because nearly every line of code here,  is calling stuff in the fastai library. So don't be afraid to look at the source code.

これはplot_top_loss、そしてfastaiライブラリの使い方を知るための素晴らしい方法です。 このコードのほぼすべての行がfastaiライブラリを呼び出しているからです。 なので、ソースコードを見ることを恐れないでください。

[[1:12:48](https://youtu.be/BWWm4AzsdLk?t=4368)]

So that's how we can look at top losses and these are perhaps the most important image classification interpretation tools that we have because it lets us see what we are getting wrong. In this case, if you are a dog and cat expert, you'll realize that the things that's getting wrong are breeds that are actually very difficult to tell apart and you'd be able to look at these and say "oh I can see why they've got this one wrong". So this is a really useful tool.

さて、我々はトップロスを見ることができます、これらはおそらく我々の持つ最も重要な画像識別解釈ツールです、これでどれが悪いのかを見ることができます。 この場合、あなたが犬猫の専門家であれば、間違ったものは実際に識別が非常に困難な品種であることに気付き、こう言うでしょう。「皆がこれを間違えたのはよく分かる」なので、これは本当に便利なツールです。

### Confusion matrix [1:13:21](https://youtu.be/BWWm4AzsdLk?t=4401)
混同マトリックス

Another useful tool, kind of, is to use something called a confusion matrix which basically shows you for every actual type of dog or cat, how many times was it predicted to be that dog or cat. But unfortunately, in this case, because it's so accurate, this diagonal basically says how it's pretty much right all the time. 
もう1つの便利なツールは、混同マトリックスというものです、基本的に各犬猫の実際のタイプと、それがどのくらい犬猫として予測されたかを示しています。。ただ残念ながら、今回はとても正確なので、この対角線は基本的にどのくらいそれが常に正しいかを示しています。

![](lesson1/10.png)

And you can see there is slightly darker ones like a five here, it's really hard to read exactly what their combination is. So what I suggest you use is instead of, if you've got lots of classes, don't use confusion matrix, but this is my favorite named function in fastai and I'm very proud of this - you can call "most confused".

ここの５つのように少し暗いものがありますが、これがどんな組み合わせであるかを認識することは難しいです。なのでたくさんのクラスがある場合は、混同マトリックスを使用しないほうがいいでしょう。でもこれは私のfastaiでのお気に入りの名前付き関数です、これを非常に誇りに思っています。 「一番混乱する」と呼びます。

### Most confused [[1:13:52](https://youtu.be/BWWm4AzsdLk?t=4432)]

```python
interp.most_confused(min_val=2)
```
```
[('american_pit_bull_terrier', 'staffordshire_bull_terrier', 5),
 ('Birman', 'Ragdoll', 5),
 ('english_setter', 'english_cocker_spaniel', 4),
 ('staffordshire_bull_terrier', 'american_pit_bull_terrier', 4),
 ('boxer', 'american_bulldog', 4),
 ('Ragdoll', 'Birman', 3),
 ('miniature_pinscher', 'chihuahua', 3),
 ('Siamese', 'Birman', 3)]
```
`most_confused` will simply grab out of the confusion matrix the particular combinations of predicted and actual that got wrong the most often. So this case, `('american_pit_bull_terrier', 'staffordshire_bull_terrier', 7)`:
- Actual `'american_pit_bull_terrier'` 
- Prediction `'staffordshire_bull_terrier'`
- This particular combination happened 7 times.

`most_confused`は、混同マトリックスから予想と実際の結果が最も頻繁に間違っていた組み合わせを取り出します。 `('american_pit_bull_terrier', 'staffordshire_bull_terrier', 7)`:の場合
- 実際の値 `'american_pit_bull_terrier'` 
- 予測値 `'staffordshire_bull_terrier'`
- この組み合わせは7回発生
 
So this is a very useful thing because you can look and say "with my domain expertise, does it make sense?"

これは非常に便利です、なぜならこれを見て「私のこの領域の専門知識を使う意味がありますか？」と言うことができるからです。

### Unfreezing, fine-tuning, and learning rates [[1:14:38](https://youtu.be/BWWm4AzsdLk?t=4478)]

Let's make our model better. How? We can make it better by using fine-tuning. So far we fitted 4 epochs and it ran pretty quickly. The reason it ran pretty quickly is that there was a little trick we used. These convolutional networks, they have many layers. We'll learn a lot about exactly what layers are, but for now, just know it goes through a lot of computations. What we did was we added a few extra layers to the end and we only trained those. We basically left most of the model exactly as it was, so that's really fast. If we are trying to build a model at something that's similar to the original pre-trained model (in this case, similar to the ImageNet data), that works pretty well.

さぁ更にモデルを良くしましょう。どうやって？微調整を行うことでより良くすることができます。これまで4エポックを適用することですばやく良くできました。これら早く実行できた理由は、我々が少しトリックを使ったからです。この畳み込みネットワークには多くの層があります。レイヤとは何かについてあとで学びますが、今のところ、これには多くの計算がいると知っているだけでいいです。我々がしたのは、最後に複数のレイヤーを追加してそれをトレーニングしたことでした。基本的にはモデルの大部分を正確にそのまま残したので、それでそれは本当に早くできます。 元の事前訓練済みモデル（これはImageNetデータの件と似ています）に似たモデルを作成する場合、これはよく動きます。


But what we really want to do is to go back and train the whole model. This is why we pretty much always use this two stage process. By default, when we call `fit` or `fit_one_cycle` on a ConvLearner, it'll just fine-tune these few extra layers added to the end and it will run very fast. It will basically never overfit but to really get it good, you have to call `unfreeze`. `unfreeze` is the thing that says please train the whole model. Then I can call fit_one_cycle again. 

でも私達が本当にしたいことは、戻ってモデル全体を訓練することです。 これが我々がほぼいつもこの2段階プロセスを踏む理由です。 デフォルトでは、ConvLearnerで `fit`または` fit_one_cycle`を呼び出すと、これは最後に追加されたこれらのいくつかのレイヤーを微調整するだけなので、非常に高速に実行されます。 これは基本的にやり過ぎないでしょうが、しかし本当にこれを良くするためには、 `unfreeze`を呼び出さなければいけません。 `unfreeze`はモデル全体を訓練するということです。 それから再びfit_one_cycleを呼び出すことができます。

```python
learn.unfreeze()
learn.fit_one_cycle(1)
```
```

Total time: 00:20
epoch  train_loss  valid_loss  error_rate
1      1.045145    0.505527    0.159681    (00:20)
```

Uh-oh. The error got much worse. Why? In order to understand why, we are actually going to have to learn more about exactly what's going on behind the scenes. So let's start out by trying to get an intuitive understanding of what's going on behind the scenes. We are going to do it by looking at pictures.

ああ、エラーがさらに悪化しました。なぜ？これを理解するためには、我々は実際にこの舞台裏で何が起きているのかを更に学ばなければいけません。では舞台裏で何がを凝っているのか直感的に理解することから始めましょう。写真を見ながらそれをやっていきます。
ええとああ。 エラーはさらに悪化しました。 どうして？ その理由を理解するために、私たちは実際に舞台裏で何が起こっているのかについてもっと学ばなければなりません。 それでは、舞台裏で何が起こっているのかを直感的に理解することから始めましょう。 私たちは写真を見てそれをやろうとしています。

[[1:16:28](https://youtu.be/BWWm4AzsdLk?t=4588)]
![](lesson1/100.png)

These pictures come from [a fantastic paper](https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf) by Matt Zeiler who nowadays is a CEO of Clarify which is a very successful computer vision startup and his supervisor for his PhD Rob Fergus. They wrote a paper showing how you can visualize the layers of a convolutional neural network. A convolutional neural network, which we will learn mathematically about what the layers are shortly, but the basic idea is that your red, green, and blue pixel values that are numbers from nought to 255 go into the simple computation (i.e. the first layer) and something comes out of that, and then the result of that goes into a second layer, and the result of that goes into the third layer and so forth. There can be up to a thousand layers of neural network. ResNet34 has 34 layers, and ResNet50 has 50 layers, but let's look at layer one. There's this very simple computation which is a convolution if you know what they are. What comes out of this first layer? Well, we can actually visualize these specific coefficients, the specific parameters by drawing them as a picture. There's actually a few dozen of them in the first layer, so we don't draw all of them. Let's just look at 9 at random. 

これらの画像はMatt Zeiler氏の[素晴らしい論文]（https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf）によるものです。彼は今非常に成功しているコンピュータビジョンのスタートアップであるClarifyのCEOで、PhDのRob Fergus氏のスーパーバイザーです。彼らは畳み込みニューラルネットワークの層を視覚化する方法について論文を書きました。畳み込みニューラルネットワークは、レイヤーの数学的な考え方については今後学びますが、基本的な考え方は、赤・緑・青のピクセル値が0から255までの値に簡単な計算でなるということです（最初の層のように）。そしてそこから出てきた結果は2番目の層に入り、さらにその結果は3番目、4番目の層に入っていきます。1000層ものニューラルネットワークにすることができます。 ResNet34には34のレイヤーがあり、ResNet50には50のレイヤーがありますが、しかしレイヤー1を確認してみましょう。あなたはこれが何か知っていれば非常に単純な畳み込みの計算ができます。この最初の層から何が出力されるか？ええ、これらの特定の係数やパラメータは、画像として実際に視覚化することができます。最初のレイヤーには実際には数十個のものがあるので、そのすべてを描画するわけではありません。ランダムに9個確認してみましょう。


[[1:17:45](https://youtu.be/BWWm4AzsdLk?t=4665)]

![](lesson1/124.png)

Here are nine examples of the actual coefficients from the first layer. So these operate on groups of pixels that are next to each other. So this first one basically finds groups of pixels that have a little diagonal line, the second one finds diagonal line in the other direction, the third one finds gradients that go from yellow to blue, and so forth. They are very simple little filters. That's layer one of ImageNet pre-trained convolutional neural net. 

これは最初のレイヤーが持つ9つの係数の例です。そしてこれらは互いに隣接するピクセルのグループに影響します。 つまり、この最初のものは基本的に小さな対角線を持つピクセルのグループを見つけ、2番目のものはその対称となる対角線を見つけ、3番目のものは黄色から青に変わる勾配を見つけます、4番目も同様です。これらは非常にシンプルな小さなフィルターです。 これはImageNetの事前に訓練された畳み込みニューラルネットの1つです。

![](lesson1/125.png)

Layer 2 takes the results of those filters and does a second layer of computation. The bottom right are nine examples of a way of visualizing one of the second layer features. AS you can see, it basically learned to create something that looks for top left corners. There are ones that learned to find right-hand curves, and little circles, etc. In layer one, we have things that can find just one line, and in layer 2, we can find things that have two lines joined up or one line repeated. If you then look over to the right, these nine show you nine examples of actual bits of the actual photos that activated this filter a lot. So in other words, the filter on the bottom right was good at finding these window corners etc. 

レイヤ2はこれらのフィルタの結果を受け取り、2番目の計算レイヤを実行します。 右下は、2番目のレイヤフィーチャの1つを視覚化する方法の9つの例です。 ご覧のとおり、基本的には左上隅を探すものを作成することを学びました。 右手の曲線や小さな円などを見つけることを学んだものがあります。レイヤ1では、1本の線だけを見つけることができるものがあり、レイヤ2では、2本の線を結合したものまたは1本の線があります。 繰り返します。 次に右を見渡せば、これら9つは、このフィルタを頻繁にアクティブにした実際の写真の実際のビットの9つの例を示しています。 したがって、言い換えれば、右下のフィルタはこれらのウィンドウの角などを見つけるのに適していました。

So this is the kind of stuff you've got to get a really good intuitive understanding for. The start of my neural net is going to find very simple gradients and lines, the second layer can find very simple shapes, the third layer can find  combination of those. 

だからこれはあなたが本当に良い直感的な理解を得るために持っているようなものです。 私のニューラルネットの始まりは、非常に単純なグラデーションと線を見つけることです、第2層は非常に単純な形状を見つけることができます、第3層はそれらの組み合わせを見つけることができます。

![](lesson1/126.png)

Now we can find repeating pattern of two dimensional objects or we can find things that joins together, or bits of text (although sometimes windows) - so it seems to find repeated horizontal patterns. There are also ones that seem to find edges of fluffy or flowery things or geometric patterns. So layer 3 was able to take all the stuff from layer 2 and combine them together.

これで、2次元オブジェクトの繰り返しパターンを見つけたり、もしくは結合したものやテキストの一部（ウィンドウの場合もある）を見つけることができます。水平線のパターンが繰り返されているように見えるものもあります。ふわふわとしたものや花のようなものや幾何学模様のようなものに見えるものもあります。なので、レイヤ3はレイヤ2からそれらすべてのものを取り出して組み合わせることができました。

![](lesson1/127.png)

Layer 4 can take all the stuff from layer 3 and combine them together. By layer 4, we got something that can find dog faces or bird legs. 

レイヤ4はレイヤ3からすべてのものを取り出して組み合わせることができます。 レイヤー4まででに、犬の顔や鳥の足を確認できます。

By layer 5, we've got something that can find the eyeballs of bird and lizards, or faces of particular breeds of dogs and so forth. So you can see how by the time you get to layer 34, you can find specific dog breeds and cat breeds. This is kind of how it works.

レイヤ5までに、鳥やトカゲの目、または特定の犬種の顔などを確認できます。 そしてレイヤー34にたどりつく頃には、特定の犬種と猫種を確認することができます。 これが一つの仕組みです。

So when we first trained (i.e. fine-tuned) the pre-trained model, we kept all of these layers that you've seen so far and we just trained a few more layers on top of all of those sophisticated features that are already being created. So now we are going back and saying "let's change all of these". We will start with where they are, but let's see if we can make them better. 

なので、事前に訓練されたモデルを最初に訓練（微調整など）したときには、これまで確認したレイヤーすべてを維持し、この洗練された性能の上に作成したいくつかのレイヤーを訓練しました。今私たちは戻って「これらすべてを変えよう」と言っているのです。ここにあるものから始めて、しかしそれらをより良くできるのかどうかを確認しましょう。

Now, it seems very unlikely that we can make layer 1 features better. It's very unlikely that the definition of a diagonal line is going to be different when we look at dog and cat breeds versus the ImageNet data that this was originally trained on. So we don't really want to change the layer 1 very much if at all. Or else, the last layers, like types of dog face seems very likely that we do want to change that. So you want this intuition, this understanding that the different layers of a neural network represents different level of semantic complexity. 

現在、レイヤ1の性能を向上させることはほとんど不可能です。 対角線の定義が訓練されたオリジナルのImagenetのデータと、犬と猫の品種を比較したときに異なることはまずありません。だからレイヤ1を変更したくはありません。 一方最後のレイヤーは犬の顔の種類のように見え、私たちがそれを変更したいと思う可能性が非常に高いでしょう。あなたはニューラルネットワークの異なったレイヤーが異なったレベルの複雑な意味を表すということを理解する感覚が欲しいです。

[[1:22:06](https://youtu.be/BWWm4AzsdLk?t=4926)]

This is why our attempt to fine-tune this model didn't work because by default, it trains all the layers at the same speed which is to say it will update those things representing diagonal lines and gradients just as much as it tries to update the things that represent the exact specifics of what an eyeball looks like, so we have to change that. 

このモデルを微調整しようとしてうまくいかなかったのはこのせいです。デフォルトでは、訓練では眼球がどのように識別されるのかと同じぐらい対角線やグラデーションを表すものが変更されてしまいます。それを変える必要があります。

To change it, we first of all need to go back to where we were before. We just broke this model, much worse than it started out. So if we just go:

これを変えるためには、まず私たちは以前の状態に戻る必要があります。 私たちはこのモデルを壊したばかりです。そこにちょうど戻るなら：

```python
learn.load('stage-1')
```
This brings back the model that we saved earlier. So let's load that back up and now our models back to where it was before we killed it.

これで以前保存したモデルを取り戻せます。ではこれをバックアップして、モデルを壊す前の状態に戻しましょう。

### Learning rate finder [[1:22:58](https://youtu.be/BWWm4AzsdLk?t=4978)]

Let's run learning rate finder. We are learning about what that is next week, but for now, just know this is the thing that figures out what is the fastest I can train this neural network at without making it zip off the rails and get blown apart. 

学習率ファインダーを実行しましょう。私たちは来週の内容を学んでいますが、今はこれをニューラルネットワークのレールからバラバラにならずに最も早く訓練する方法だと考えてください。

```python
learn.lr_find()
learn.recorder.plot()
```
![](lesson1/11.png)

This will plot the result of our LR finder and what this basically shows you is this key parameter called a learning rate. The learning rate basically says how quickly am I updating the parameters in my model. The x-axis one here shows me what happens as I increase the learning rate. The y axis show what the loss is. So you can see, once the learning rate gets passed 10^-4, my loss gets worse. It actually so happens, in fact I can check this if I press <kbd>shift</kbd>+<kbd>tab</kbd> here, my learning defaults to 0.003. So you can see why our loss got worse. Because we are trying to fine-tune things now, we can't use such a high learning rate. So based on the learning rate finder, I tried to pick something well before it started getting worse. So I decided to pick `1e-6`. But there's no point training all the layers at that rate, because we know that the later layers worked just fine before when we were training much more quickly. So what we can actually do is we can pass a range of learning rates to `learn.fit_one_cycle`. And we do it like this:

これはLRファインダーという、学習率と呼ばれる大事なパラメータの結果をプロットします。学習率は基本的にモデルをどのくらい早く訓練するかを言います。このX軸は学習率の増加を示しています。Y軸は損失の大きさを示しています。つまり、学習率が10 ^ -4を過ぎると損失は非常に悪化します。実際にそうなります。実際、ここで<kbd> shift </kbd> + <kbd> tab </kbd>を押してこのことを確認できます。ここでの学習率のデフォルトは0.003です。これが損失が悪化した理由です。今はこれを微調整しようとしているので、このような高い学習率は使えません。そこで学習率ファインダーに基づき、これが悪化し始める前のものを選択しようとします。そこで私は `1e-6`を選ぶことにしました。しかし、この速度ですべてのレイヤーをトレーニングすることには意味がない。なので実際には、 `learn.fit_one_cycle`にさまざまな学習率を渡します。このように：

```python
learn.unfreeze()
learn.fit_one_cycle(2, max_lr=slice(1e-6,1e-4))
```
```
Total time: 00:41
epoch  train_loss  valid_loss  error_rate
1      0.226494    0.173675    0.057219    (00:20)
2      0.197376    0.170252    0.053227    (00:20)
```

You use this keyword in Python called `slice` and that can take a start value and a stop value and basically what this says is train the very first layers at a learning rate of 1e-6, and the very last layers at a rate of 1e-4, and distribute all the other layers across that (i.e. between those two values equally). 

Pythonで`slice`と呼ばれるキーワードを使用すると開始時の値と終了時の値を取得できます、これらが基本的に示しているのは1e-6の学習率で一番最初のレイヤーを訓練すること、 最後のレイヤーは1e-4,で、かつ他の全てのレイヤーはこれらの値を（例えば2つの値の平均などで）分配します。


### How to pick learning rates after unfreezing [[1:25:23](https://youtu.be/BWWm4AzsdLk?t=5123)]

A good rule of thumb is after you unfreeze (i.e. train the whole thing), pass a max learning rate parameter, pass it a slice, make the second part of that slice about 10 times smaller than your first stage. Our first stage defaulted to about 1e-3 so it's about 1e-4. And the first part of the slice should be a value from your learning rate finder which is well before things started getting worse. So you can see things are starting to get worse maybe about here:

大まかな目安としては、フリーズを解除したあと（つまり全体をトレーニングした後）、最大の学習率をパラメーターとして渡し、スライスに渡し、このスライスの2番目の部分は最初の段階の約10分の1にすることです。 今回の最初のステージはデフォルトで約1e-3だったので、つまりそれは約1e-4です。 かつこのスライスの最初の部分は、損失が悪化し始めるかなり前の時点で学習率ファインダーの値であるべきです。 なので、ここで結果が悪化していていることがわかります。

![](lesson1/128.png)

So I picked something that's at least 10 times smaller than that.

だから私はこれより少なくとも10倍小さいものを選びました。

If I do that, then the error rate gets a bit better. So I would perhaps say for most people most of the time, these two stages are enough to get pretty much a world-class model. You won't win a Kaggle competition, particularly because now a lot of fastai alumni are competing on Kaggle and this is the first thing that they do. But in practice, you'll get something that's about as good in practice as the vast majority of practitioners can do. 

そうすることでエラー率は少し良くなります。なのでほとんどの人にとってはこの2つのステップで十分世界クラスのモデルとなるには十分です。でもfastaiのたくさんの卒業生がKaggleで競っているので、あなたはKaggleコンテストに勝つことはできません、でもこれが彼らがしてきた最初のことなのです。 一方で実際には、専門家の大多数がやれることと同じくらい、実務に使えるものが手に入れられています。

## ResNet50 [[1:26:55](https://youtu.be/BWWm4AzsdLk?t=5215)]

We can improve it by using more layers and we will do this next week but by basically doing a ResNet50 instead of ResNet34. And you can try running this during the week if you want to. You'll see it's exactly the same as before, but I'm using ResNet50. 

もっと多くのレイヤーを利用することでこれを改善できます、そのことは来週行いますが、基本的にResNet34の代わりにResNet50をやります。気になるなら来週までの授業の間にこれを実行することができます。以前と全く同じですが、しかし私はResNet50を使います。

```python

data = ImageDataBunch.from_name_re(path_img, fnames, pat, ds_tfms=get_transforms(), size=320, bs=bs//2)
data.normalize(imagenet_stats)
```

```python

learn = ConvLearner(data, models.resnet50, metrics=error_rate)
```

What you'll find is it's very likely if you try to do this, you will get an error and the error will be your GPU has ran out of memory. The reason for that is that ResNet50 is bigger than ResNet34, and therefore, it has more parameters and use more of your graphics card memory, just totally separate to your normal computer RAM, this is GPU RAM. If you're using the default Salamander,  AWS, then you'll be having a 16G of GPU memory. The card I use most of the time has 11G GPU memory, the cheaper ones have 8G. That's kind of the main range you tend to get. If yours have less than 8G of GPU memory, it's going to be frustrating for you. 

もしこれをやろうとするなら、いろいろな発見があるでしょう。あなたはエラーに遭遇するでしょう、どれはGPUがメモリを使い果たしたというエラーです。その理由はResnet５０がResnet34より大きく、そのために通常のコンピュータのRAMとは全く別の、更に性能のよいグラフィックカードを使います、GPURAMというものです。デフォルトのAWSのSalamanderを使用している場合は、16GのGPUメモリがあります。 私が最もよく使うカードは11GのGPUメモリがあります、安いものなら8Gのメモリです。これがあなたが手に入れられる主な範囲でしょう。あなたのGPUメモリが8G以下の場合はイライラの原因になります。

It's very likely that if you try to run this, you'll get an out of memory error and that's because it's just trying to do too much - too many parameter updates for the amount of RAM you have. That's easily fixed. `ImageDataBunch` constructor has a parameter at the end `bs` - a batch size. This basically says how many images do you train at one time. If you run out of memory, just make it smaller.

これを実行するならエラーに出会う可能性が高い、なぜならRAMの量に比べてパラメータ更新が多すぎるためです。これは簡単に修正できます。`ImageDataBunch`コンストラクタは、最後に` bs` - バッチサイズのパラメータがあるます。 これは基本的に一度に何個の画像を訓練しているかを指示します。 メモリが足りなくなった場合は、これを小さくしてください。

It's fine to use a smaller bath size. It might take a little bit longer. That's all. So that's just one number you'll need to try during the week. 

もっと小さいバスサイズを使うのもいいでしょう。 もう少し時間がかかるようになるかもしれません。 これが全部です。なのでこれはあなたが今週中に試してみるべきただ一つの数字です。

```python
learn.fit_one_cycle(8, max_lr=slice(1e-3))
```
```
Total time: 07:08
epoch  train_loss  valid_loss  error_rate
1      0.926640    0.320040    0.076555    (00:52)
2      0.394781    0.205191    0.063568    (00:52)
3      0.307754    0.203281    0.069036    (00:53)
4      0.244182    0.160488    0.054682    (00:53)
5      0.185785    0.153520    0.049214    (00:53)
6      0.157732    0.149660    0.047163    (00:53)
7      0.107212    0.136898    0.043062    (00:53)
8      0.097324    0.136638    0.042379    (00:54)
```

Again, we fit it for a while and we get down to 4.2% error rage. So this is pretty extraordinary. I was pretty surprised because when we first did in the first course, this cats vs. dogs, we were getting somewhere around 3% error for something where you've got a 50% chance of being right and the two things look totally different. So the fact that we can get 4.2% error for such a fine grain thing, it's quite extraordinary. 

繰り返すと、これを適用することで、エラー率が4.2％に下がります。 これはかなり特別です。 最初のコースではこの犬対猫はまったくことなる２つの50%のチャンスで正しくなるものが3%の誤差に収まったので非常に驚きました。このような微調整で4.2％のエラー率に収まるという事実は、非常に特別なことなのです。

### Interpreting the results again [1:29:41](https://youtu.be/BWWm4AzsdLk?t=5381)
結果をもう一度解釈する

```python
interp = ClassificationInterpretation.from_learner(learn)
interp.most_confused(min_val=2)
```
```
[('Ragdoll', 'Birman', 7),
 ('american_pit_bull_terrier', 'staffordshire_bull_terrier', 6),
 ('Egyptian_Mau', 'Bengal', 6),
 ('Maine_Coon', 'Bengal', 3),
 ('staffordshire_bull_terrier', 'american_pit_bull_terrier', 3)]
```

You can call the most_confused here and you can see the kinds of things that it's getting wrong. Depending on when you run it, you're going to get slightly different numbers, but you'll get roughly the same kind of things. So quite often, I find the Ragdoll and Birman are things that it gets confused. I actually have never heard of either of those things, so I actually looked them up and found a page on the cat site called "Is this a Birman or Ragdoll kitten?" and there was a long thread of cat experts arguing intensely about which it is. So I feel fine that my computer had problems.   

most_confusedをここで呼び出すと、間違えた種類のものを確認できます。実行タイミングによっては、微妙に異なる数になりますが、しかしほぼ同じ種類のものでしょう。RagdollとBirmanは非常によく間違われるものだと思います。私はこの二種類の犬をどちらも実際に聞き及んだことはないので、調べてみたところ「これはRagdollとBirmanのどちらですか？」という猫に関するサイトを見つけ、それがどちらであるか専門家が激しく議論している長いスレッドがありました。なので私のコンピュータに問題があったのはいいことですね。


![](lesson1/129.png)

I found something similar, I think it was this pitbull versus staffordshire bull terrier, apparently the main difference is the particular kennel club guidelines as to how they are assessed. But some people thing that one of them might have a slightly redder nose. So this is the kind of stuff where actually even if you're not a domain expert, it helps you become one. Because I now know more about which kinds of pet breeds are hard to identify than I used to. So model interpretation works both ways. 

似たようなものを見つけました、確かpitbull対staffordshire bull terrierだったと思います。主な明白な違いは特定の専門家のガイドラインによる評価方法です。しかし、何人かの人々はそのうちの1つでわずかに赤い鼻を持つっていると考えています。なのでこれはあなたが専門家でなくともこの中の一人になれることに十分役立ちます。私は今これらの品種のペットが識別することが非常に難しいことをこれを使って知っています。なので、モデルの解釈は両方の道で働きます。

## Homework [[1:30:58](https://youtu.be/BWWm4AzsdLk?t=5458)]

So what I want you to do this week is to run this notebook, make sure you can get through it, but then I really want you to do is to get your own image dataset and actually Francisco is putting together a guide that will show you how to download data from Google Images so you can create your own dataset to play with. But before I do, I want to show you how to create labels in lots of different ways because your dataset where you get it from won't necessarily be that kind of regex based approach. It could be in lots of different formats. So to show you how to do this, I'm going to use the MNIST sample. MNIST is a picture of hand drawn numbers - just because I want to show you different ways of creating these datasets. 

今週中にしてほしいことはこのノートブックを実行し、それが想定通りにできることを確認することです、けれども本当にしてほしいことはあなた自身の画像データセットでです、実際にFrancisco はGoogleImageからデータセットをダウンロードしてこれを遊ぶ方法を書きました。けれどここで取得したものは必ずしも正規表現ベースのものではないため、ラベルを作成するさまざまな方法を示します。それは様々に異なったフォーマットでしょう。それを説明するためにMNISTサンプルを使います。MNISTは手書きの数字画像です - なぜならこのデータセットから作成する様々な方法を示したいからです。

```python
path = untar_data(URLs.MNIST_SAMPLE); path
```

```python
path.ls()
```
```
['train', 'valid', 'labels.csv', 'models']
```

You see there are a training set and the validation set already. So basically the people that put together this dataset have already decided what they want you to use as a validation set. 

訓練セットと評価セットが既に用意されていることがわかります。なので基本的にこのデータセットをまとめた人たちは、検証セットとして使ってほしいものを既に決めています。

### Scenario 1: Labels are folder names
ラベルはフォルダ名です

```python
(path/'train').ls()
```
```
['3', '7']
```

There are a folder called 3 and a folder called 7. Now this is really common way to give people labels. Basically it says everything that's a three, I put in a folder called three. Everything that's a seven, I'll put in a folder called seven. This is often called an "ImageNet style dataset" because this is how ImageNet is distributed. So if you have something in this format where the labels are just whatever the folders are called, you can say `from_folder`.

ここに3という名前のフォルダと7という名前のフォルダがあります。これが、人々にラベルを付けるためのごく一般的な方法です。 基本的にこれはすべて3であることを示すので、私は3と呼ばれるフォルダーに入れました。 7とつくもの全ては、7という名前のフォルダーに入れます。 これはImageNetの配布方法でもあるため、「ImageNetスタイルのデータセット」とよく呼ばれます。もしあなたがこの形式でフォルダにラベルを持つものがあるなら `from_folder`呼びましょう。

```python
tfms = get_transforms(do_flip=False)
data = ImageDataBunch.from_folder(path, ds_tfms=tfms, size=26)
```

This will create an ImageDataBunch for you and as you can see it created the labels:

これはImageDataBunchを作成し、中身を確認できるようにラベルを作成しました：

```python
data.show_batch(rows=3, figsize=(5,5))
```
![](lesson1/12.png)


### Scenario 2: CSV file [[1:33:17](https://youtu.be/BWWm4AzsdLk?t=5597)]

Another possibility, and for this MNIST sample, I've got both, it might come with a CSV file that would look something like this.

他の可能性としては、このMNISTサンプルの場合、両方共に、何らかのCSVファイルが付属しているかもしれません。

```python
df = pd.read_csv(path/'labels.csv')
df.head()
```

![](lesson1/130.png)

For each file name, what's its label. In this case, labels are not three or seven, they are 0 or 1 which basically is it a 7 or not. So that's another possibility. If this is how your labels are, you can use `from_csv`:

各ファイル名のラベルは何か。 この場合では、ラベルは3または7ではなく、0または1で、基本的には7もしくはそれ以外です。なのでこれは別の可能性です。このようなラベルであれば、 `from_csv`が使えます。

```python
data = ImageDataBunch.from_csv(path, ds_tfms=tfms, size=28)
```

And if it is called `labels.csv`, you don't even have to pass in a file name. If it's called something else, then you can pass in the `csv_labels` 

そしてそれが `labels.csv`と呼ばれていれば、ファイル名を渡す必要すらありません。 他の名前で呼ばれているのなら、 `csv_labels`を渡すことができます。

```python
data.show_batch(rows=3, figsize=(5,5))
data.classes
```
```
[0, 1]
```

![](lesson1/13.png)



### Scenario 3: Using regular expression
正規表現を使う

```python
fn_paths = [path/name for name in df['name']]; fn_paths[:2]
```

```
[PosixPath('/home/jhoward/.fastai/data/mnist_sample/train/3/7463.png'),
 PosixPath('/home/jhoward/.fastai/data/mnist_sample/train/3/21102.png')]
```

This is the same thing, these are the folders. But I could actually grab the label by using a regular expression. We've already seen this approach:

これらは同じことで、これらはフォルダです。けれど正規表現を利用してラベルを取得することができました。私たちはすでにこのアプローチを見ています：


```python
pat = r"/(\d)/\d+\.png$"
data = ImageDataBunch.from_name_re(path, fn_paths, pat=pat, ds_tfms=tfms, size=24)
data.classes
```

```
['3', '7']
```



### Scenario 4: Something more complex [[1:34:21](https://youtu.be/BWWm4AzsdLk?t=5661)]
もっと複雑なもの

You can create an arbitrary function that extracts a label from the file name or path. In that case, you would say `from_name_func`:

ファイル名またはパスからラベルを抽出する任意の関数を作成できます。 その場合、 `from_name_func`を使うでしょう。

```python
data = ImageDataBunch.from_name_func(path, fn_paths, ds_tfms=tfms, size=24,
        label_func = lambda x: '3' if '/3/' in str(x) else '7')
data.classes
```



### Scenario 5: You need something even more flexible
もっと柔軟なものが必要なとき

If you need something even more flexible than that, you're going to write some code to create an array of labels. So in that case, you can just use `from_lists` and pass in the array.

それ以上の柔軟性が必要な場合は、ラベルの配列を作成するためのコードを書くことになります。 その場合は、 `from_lists`を使って配列を渡すことができます。

```python
labels = [('3' if '/3/' in str(x) else '7') for x in fn_paths]
labels[:5]
```

```python
data = ImageDataBunch.from_lists(path, fn_paths, labels=labels, ds_tfms=tfms, size=24)
data.classes
```

So you can see there's lots of different ways of creating labels. So during the week, try this out.

ラベルを作成する方法はたくさんあります。 なので今週中に、これを試してみてください。

Now you might be wondering how would you know to do all these things? Where am I going to find this kind of information? So I'll show you something incredibly cool. You know how to get documentation:

あなたはこれら全てのことを行うことをどうやって知ることができるのだろうかと疑問に思うでしょうか？これらの情報はどこで手に入るか？私は信じられないほどクールなものをあなたにお見せします。あなたはドキュメントを入手する方法を知っています。

```python
doc(ImageDataBunch.from_name_re)
```

[[Show in docs](https://docs.fast.ai/vision.data.html#ImageDataBunch.from_name_re)]



![](lesson1/131.png)



Every single line of code I just showed you, I took it this morning and I copied and pasted it from the documentation. So you can see here the exact code that I just used. So the documentation for fastai doesn't just tell you what to do, but step to step how to do it. And here is perhaps the coolest bit. If you go to [fastai/fastai_docs](https://github.com/fastai/fastai_docs) and click on [docs/src](https://github.com/fastai/fastai_docs/tree/master/docs_src).

今ここで示したコードの１行ごとを、今朝ドキュメントからコピーして貼り付けました。なので私が今使った正確なコードを確認できます。fastaiのドキュメントはただあなたに何をすべきかを教えるのではなく、どのようにそれが動くか段階を踏んで教えてくれます。おそらくそれが最もクールなものです。[fastai/fastai_docs](https://github.com/fastai/fastai_docs) へ行って [docs/src](https://github.com/fastai/fastai_docs/tree/master/docs_src)をクリックした場合は。

All of our documentation is actually just Jupyter Notebooks. You can git clone this repo and if you run it, you can actually run every single line of the documentation yourself.

この全てのドキュメントは実際にはJupyter Notebooksです。 このレポジトリをgit cloneすることができますし、もし実行すれば、実際にはドキュメントの各行を自分で実行することができます。

This is the kind of the ultimate example to me of experimenting. Anything that you read about in the documentation, nearly everything in the documentation has actual working examples in it with actual datasets that are already sitting in there in the repo for you. So you can actually try every single function in your browser, try seeing what goes in and try seeing what comes out. 

これは私にとって究極の実験ですす。 ドキュメントの中で読んでいるもの、ドキュメントの中のほとんどすべてはあなたのリポジトリの中で既に実際のデータセットが用意されています。なので個々の機能をブラウザで試すことができるので、この入出力を確認してみてください。



[[1:37:27](https://youtu.be/BWWm4AzsdLk?t=5847)]

**Question**: Will the library use multi GPUs in parallel by default? 
ライブラリはデフォルトでマルチGPUを並列に使用しますか？

The library will use multiple CPUs by default but just one GPU by default. We probably won't be looking at multi GPU until part 2. It's easy to do and you'll find it on the forum, but most people won't be needing to use that now.

ライブラリはデフォルトで複数のCPUを使用しますが、デフォルトではGPUは一つのみです。 パート2まではマルチGPUを検討することはおそらくないでしょう。それをすることは簡単で、フォーラムで確認できますが、ほとんどの人は今それを使う必要はないでしょう。

**Question**: Can the library use 3D data such as MRI or CAT scan?
ライブラリはMRIやCATといった3Dデータも扱えますか？

Yes, it can. ANd there is actually a forum thread about that already. Although that's not as developed as 2D yet but maybe by the time the MOOC is out, it will be.

はい、可能です。そしてそれらは既に実際にフォーラムのスレッドがあります。それはまだ2D画像ほどには発展していませｓんが、このMOOCが出るころにはそうなっているでしょう。


### Splunk Anti-Fraud Software [[1:38:10](https://youtu.be/BWWm4AzsdLk?t=5890)]

[blog](https://www.splunk.com/blog/2017/04/18/deep-learning-with-splunk-and-tensorflow-for-security-catching-the-fraudster-in-neural-networks-with-behavioral-biometrics.html)

Before I wrap up, I'll just show you an example of the kind of interesting stuff that you can do by doing this kind of exercise. 
授業を終わる前に、この宿題をすることであなたができるようになるとても面白い例を見せます。

Remember earlier I mentioned that one of our alumni who works at Splunk which is a NASDAQ listed big successful company created this new anti-fraud software. This is actually how he created it as part of a fastai part 1 class project:

先ほど言及したSplunkで働いているNASDAQ上場の大いに成功した企業で働いている、この講義の卒業生は、この新しい不正防止ソフトウェアを作成しました。これは実際に彼がfastaiのパート1のクラスのプロジェクトで作成したものです：

![](lesson1/132.jpg)


He took the telemetry of users who had Splunk analytics installed and watched their mouse movements and he created pictures of the mouse movements. He converted speed into color and right and left clicks into splotches. He then took the exact code that we saw with an earlier version of the software and trained a CNN in exactly the same way we saw and used that to train his fraud model. So he took something which is not obviously a picture and he turned it into a picture and got these fantastically good results for a piece of fraud analysis software. 

Splunk分析をインストールしたユーザーのテレメトリを使ってマウスの動きを観察し、マウスの動きを示す画像を作成しました。 彼はスピードをカラーに、左右のクリックを斑点に変換しました。 それから彼は私達が以前のバージョンのソフトウェアで教えた正確なコードを使い、私達が見たものと全く同じ方法でCNNを訓練し、それを使って詐欺モデルを訓練しました。 それで彼は明らかに画像ではない何かを取得し、画像に変えて、そして詐欺分析ソフトウェアの一部としｔ素晴らしい成果を得ました。

So it pays to think creatively. So if you are wanting to study sounds, a lot of people that study sounds do it by actually creating a spectrogram image and then sticking that into a ConvNet. So there's a lot of cool stuff you can do with this. 

創造的に考えることは役に立ちます。 あなたが音声について研究したいのであれば、音声を研究している多くの人々は実際にスペクトログラム画像を作成してそれをConvNetに変換することによって研究しています。なのでこれを利用してできることはたくさんあります。

So during the week, get your GPU going, try and use your first notebook, make sure that you can use lesson 1 and work through it. Then see if you can repeat the process on your own dataset. Get on the forum and tell us any little success you had. Any constraints you hit, try it for an hour or two but if you get stuck, please ask. If you are able to successfully build a model with a new dataset, let us know! I will see you next week.

では集の間にGPUを手に入れて最初のnotebookを試していて、lesson1を通じて動くことを確認してください。それからあなた自身のデータセットで同じことができるかどうかを見てみてください。フォーラムに参加して、上手く行ったことを少しでも教えてください。あなたがどんな問題にあたっても、１〜２時間は試してみてください。しかしどうにもならなくなったら尋ねてみてください。新しいデータセットでモデルを上手く作成できたら、ぜひ教えてください！
では来週お会いしましょう。

