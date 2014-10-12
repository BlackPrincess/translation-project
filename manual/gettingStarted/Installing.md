<!--
# Installing Play
-->
# Play のインストール

<!--
## Prerequisites
-->
## 前提条件

<!--
To run the Play framework, you need [JDK 6 or later](http://www.oracle.com/technetwork/java/javase/downloads/index.html). 
-->
Play framework の実行には、[JDK 6以降](http://www.oracle.com/technetwork/java/javase/downloads/index.html) が必要です。

<!--
> If you are using MacOS, Java is built-in. If you are using Linux, make sure to use either the Sun JDK or OpenJDK (and not gcj, which is the default Java command on many Linux distros). If you are using Windows, just download and install the latest JDK package.

> Note, Java 7 pre update 9 on MacOS has a bug that causes problems with futures and iteratees, including making large file uploads hang.  If using Java 7 on MacOS, make sure you are using the latest version.
-->
> MacOS をお使いであれば、Java はプリインストールされています。Linux をお使いの場合は、Sun JDK か OpenJDK をインストール (多くの Linux ディストリビューションで標準になっている gcj ではなく) してください。Windows をお使いの場合、最新の JDK パッケージをダウンロード・インストールしてください。

<!--
Be sure to have the `java` and `javac` commands in the current path (you can check this by typing `java -version` and `javac -version` at the shell prompt). 
-->
カレントパスで `java` と `javac` コマンドが利用できることを確認してください。(これはプロンプトで `java -version` と `javac -version` と入力することでチェックできます。)

<!--
## Download the binary package
-->
## バイナリパッケージのダウンロード

### Using Typesafe Activator

Play can be installed using [Typesafe Activator](http://typesafe.com/activator).  The documentation on this page is about installing the Play standalone distribution.  If you would like to use Typesafe Activator, then follow the instructions [here](http://typesafe.com/platform/getstarted) to install Play.

### Using Play standalone

Download the latest [Play standalone distribution](http://www.playframework.com/download) and extract the archive to a location where you have both read **and write** access. (Running `play` writes some files to directories within the archive, so don't install to `/opt`, `/usr/local` or anywhere else you’d need special permission to write to.)

<!--
## Add the play script to your PATH
-->
## play スクリプトへパスを通す

<!--
For convenience, you should add the framework installation directory to your system PATH. On UNIX systems, this means doing something like:
-->
利便性のため、Play のインストール先ディレクトリを PATH 環境変数に追加しておきましょう。例えば、Unix 系の OS をお使いの場合は、次のように設定します:

```bash
export PATH=$PATH:/relativePath/to/play
```

<!--
On Windows you’ll need to set it in the global environment variables. This means update the PATH in the environment variables and don't use a path with spaces.
-->
Windows では、システム環境変数を設定する必要があります。これは環境変数で設定されているパスを更新することを意味し、スペースを含むパスを使わないようにしてください。

> If you’re on UNIX, make sure that the `play` script is executable.
> 
> Otherwise do a:
> ```bash
> chmod a+x play
> chmod a+x framework/build
> ```

> If you're behind a proxy make sure to define it with `set HTTP_PROXY=http://<host>:<port>` on Windows or `export  HTTP_PROXY=http://<host>:<port>` on UNIX.

<!--
## Check that the play command is available
-->
## play コマンドの起動確認

<!--
From a shell, launch the `play help` command. 

```bash
$ play help
```
-->
シェルで `play help` コマンドを実行しましょう。

<!--
If everything is properly installed, you should see the basic help:
-->
インストールが正しく行えていれば、ヘルプが表示されるはずです。

[[images/play.png]]

<!--
> **Next:** [[Creating a new application | NewApplication]]
-->
> **Next:** [[新規アプリケーションを作成する | NewApplication]]
