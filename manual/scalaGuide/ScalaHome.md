<!--
# Play for Scala developers
-->
# Scala 開発者のための Play

<!--
The Scala API for Play application developers is available in the `play.api` package. 
-->
Play アプリケーションは、`play.api` パッケージ内にある Scala API を使って開発することができます。

<!--
> The API available directly inside the `play` package (such as `play.mvc`) is reserved for Java developers. As a Scala developer, look at `play.api.mvc`.
-->
> (`play.mvc` のような) `play` パッケージ内の API は Java 開発者に予約されています。Scala 開発者は `play.api.mvc` などを参照してください。

<!--
## Main concepts
-->
## 主要なコンセプト

1. [[HTTP programming | ScalaActions]]
    1. [[Actions, Controllers and Results | ScalaActions]]
    1. [[HTTP routing | ScalaRouting]]
    1. [[Manipulating results | ScalaResults]]
    1. [[Session and Flash scopes | ScalaSessionFlash]]
    1. [[Body parsers | ScalaBodyParsers]]
    1. [[Actions composition | ScalaActionsComposition]]
    1. [[Content negotiation | ScalaContentNegotiation]]
1. [[Asynchronous HTTP programming | ScalaAsync]]
    1. [[Handling asynchronous results | ScalaAsync]]
    1. [[Streaming HTTP responses | ScalaStream]]
    1. [[Comet sockets | ScalaComet]]
    1. [[WebSockets | ScalaWebSockets]]
1. [[The template engine | ScalaTemplates]]
    1. [[Templates syntax | ScalaTemplates]]
    1. [[Common use cases | ScalaTemplateUseCases]]
1. [[Form submission and validation | ScalaForms]]
    1. [[Handling form submission | ScalaForms]]
    1. [[Protecting against CSRF|ScalaCsrf]]
    1. [[Custom Validations|ScalaCustomValidations]]
    1. [[Custom Field Constructors|ScalaCustomFieldConstructors]]
1. [[Working with Json | ScalaJson]]
    1. [[JSON basics | ScalaJson]]
    1. [[JSON with HTTP | ScalaJsonHttp]]
    1. [[JSON Reads/Writes/Format Combinators | ScalaJsonCombinators]]
    1. [[JSON Transformers | ScalaJsonTransformers]]
    1. [[JSON Macro Inception | ScalaJsonInception]]
1. [[Working with XML | ScalaXmlRequests]]
    1. [[Handling and serving XML requests | ScalaXmlRequests]]
1. [[Handling file upload | ScalaFileUpload]]
    1. [[Direct upload and multipart/form-data | ScalaFileUpload]]
1. [[Accessing an SQL database | ScalaDatabase]]
    1. [[Configuring and using JDBC | ScalaDatabase]]
    1. [[Using Anorm to access your database | ScalaAnorm]]
    1. [[Integrating with other database access libraries | ScalaDatabaseOthers]]
1. [[Using the Cache | ScalaCache]]
    1. [[The Play cache API | ScalaCache]]
1. [[Calling WebServices | ScalaWS]]
    1. [[The Play WS API  | ScalaWS]]
    1. [[Connecting to OpenID services | ScalaOpenID]]
    1. [[Accessing resources protected by OAuth | ScalaOAuth]]
1. [[Integrating with Akka | ScalaAkka]]
    1. [[Setting up Actors and scheduling asynchronous tasks | ScalaAkka]]
1. [[Internationalization | ScalaI18N]]
    1. [[Messages externalisation and i18n | ScalaI18N]]
1. [[The application Global object | ScalaGlobal]]
    1. [[Application global settings | ScalaGlobal]]
    1. [[Intercepting requests | ScalaInterceptors]]
1. [[Testing your application | ScalaTestingYourApplication]]
    1. [[Testing with ScalaTest | ScalaTestingWithScalaTest]]
    1. [[Writing functional tests with ScalaTest | ScalaFunctionalTestingWithScalaTest]]
    1. [[Testing with specs2 | ScalaTestingWithSpecs2]]
    1. [[Writing functional tests with specs2 | ScalaFunctionalTestingWithSpecs2]]
    
<!--
## Advanced topics
-->
## 上級編

<!--
1. [[Handling data streams reactively | Iteratees]]
    1. [[Iteratees | Iteratees]]
    1. [[Enumerators | Enumerators]]
    1. [[Enumeratees | Enumeratees]]
1. [[HTTP Architecture | HttpApi]]
    1. [[HTTP API | HttpApi]]
    1. [[HTTP Filters | ScalaHttpFilters]]
1. [[Dependency Injection | ScalaDependencyInjection]]
    1. [[Controller Injection | ScalaDependencyInjection]]
    1. [[Example Projects | ScalaDependencyInjection]]
1. [[Reverse routing | ScalaJavascriptRouting]]
    1. [[Javascript Routing | ScalaJavascriptRouting]]
1. [[Extending Play|ScalaPlugins]]
    1. [[Writing Plugins|ScalaPlugins]]
-->
1. [[反応的なストリーム処理 | Iteratees]]
    1. [[Iteratee | Iteratees]]
    1. [[Enumerator | Enumerators]]
    1. [[Enumeratee | Enumeratees]]
1. [[HTTP アーキテクチャ | HttpApi]]
    1. [[HTTP API | HttpApi]]
    1. [[HTTP フィルター | ScalaHttpFilters]]
1. [[依存性の注入 | ScalaDependencyInjection]]
    1. [[コントローラの注入 | ScalaDependencyInjection]]
    1. [[プロジェクトの例 | ScalaDependencyInjection]]
1. リバースルーティング
    1. [[Javascriptのルーティング | ScalaJavascriptRouting]]
1. [[Play を拡張する|ScalaPlugins]]
    1. [[プラグインの書き方|ScalaPlugins]]

<!--
## Tutorials
-->
## チュートリアル

<!--
1. [[Your first application | ScalaTodoList]]
-->
1. [[はじめてのアプリケーション | ScalaTodoList]]
