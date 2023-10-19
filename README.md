## Say Hello Module

Ini adalah contoh module yang akan kita diconsume oleh aplikasi Go. Module ini hanya mengembalikan string `"Hello"` dengan cara memanggil function `SayHello()`. Penamaan function `SayHello()` diawali dengan huruf kapital supaya bisa diexport secara publik. Dalam contoh ini, aplikasi Go yang akan consume module ini ada di [https://github.com/malvinval/learn-go-modules/tree/master/say-hello-consumer](https://github.com/malvinval/learn-go-modules/tree/master/say-hello-consumer) dengan nama file `app.go`.

**Module sayhello ini akan kita namakan sebagai github.com/malvinval/gosayhello**