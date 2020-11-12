---
layout: lecture
title: "Security and Privacy"
presenter: Jon
video:
  aspect: 56.25
  id: OBx_c-i-M8s
---

دنیا جای ترسناکی است، و آن بیرون همه میخواهند به شما آسیب برسانند.

باشه، شاید هم اینطور نباشد، اما همچنان شما نمیخواهید اسرارتان را جار بزنید.
امنیت (و حریم شخصی) عموما درباره بلند کردن حفاض ها در برابر محاجمان است. مدل تحدیدت
را پیدا کن ، سپس سازوکار امنیتی خود را دور آن بسازید! اگر مدل تحدید ان.اس .ای یا موساد باشند،
_احتمالا_ قرار است کهدوران سختی را بگزرانید.

راه های _زیادی_ برای امن تر کردن شخصیت مجازی شما وجود دارند.
اینجا قرار است به چیزهای سطح بالای زیادی اشاره کنیم، اما این یک روند است،
و در این جهت، خود آموزی یکی از بهترین کار هاییست که میتوانید انجام دهید. پس:

## افراد صحیح را دنبال کنید

یکی از بهترین راه های افزایش امنیت شما، این است که بدانید
 دنبال کردن افراد دیگری است که راجب امنیت سخن میگویند، چگونه است. چند پیشنهاد:

- [@TroyHunt](https://twitter.com/TroyHunt)
- [@SwiftOnSecurity](https://twitter.com/SwiftOnSecurity)
- [@taviso](https://twitter.com/taviso)
- [@thegrugq](https://twitter.com/thegrugq)
- [@tqbf](https://twitter.com/tqbf)
- [@mattblaze](https://twitter.com/mattblaze)
- [@moxie](https://twitter.com/moxie)

همچنان [این
لیست](https://heimdalsecurity.com/blog/best-twitter-cybersec-accounts/)
را برای پیشنهاد های بیشتر ببینید.

## پیشنهاد های عمومی امنیت

تک سالیدتری یک لیست خیلی خوب از  [باید ها و نباید ها برای خبرنگاران](https://techsolidarity.org/resources/basic_security.htm)
که تعداد زیادی پیشنهاد منطقی دارد، و به میزان قابل قبولی به روز است. @thegrugq
هم یک پست بلاگ خوب روی [پیشنهاد امنیت مسافرتی](https://medium.com/@thegrugq/stop-fabricating-travel-security-advice-35259bf0e869)
دارد که ارزش خواندن دارد. قرار است اینجا اکثرا پیشنهادات این منبابع را تکرار کنیم. همچنین یک [مسدود کننده داده یو اس بی](https://amzn.com/B00QRRZ2QM) بگیرید, جون [یو اس بی ترسناک است](https://www.bleepingcomputer.com/news/security/heres-a-list-of-29-different-types-of-usb-attacks/).

## احراز هویت

اولین کاری که باید انجام دهید, البته اگر هنوز انجام نداده اید,
 دانلود کردن یک برنامه مدیریت کلمات عبور است. اینها چند تا از نرم افزار های مناسب هستند:

- [1password](https://1password.com/)
- [KeePass](https://keepass.info/)
- [BitWarden](https://bitwarden.com/)
- [`pass`](https://www.passwordstore.org/)

اگر به معنی واقعی کلمه پارانوئید هستید, یکی را استفاده کنید
که کلمات عبور را به صورت رمز شده روی کامپیوتر محلی شما
ذخیره میکند, نه آنکه به صورت متن ساده  و در یک سرور ذخیره کند.
با استفاده از نمرم افزار، همین الان برای همه سایت هایی که بهشان اهمیت
میدهید رمز بسازید. سپس, احراز هویت دو مرحله ای را فعال کنید, با یک
[FIDO/U2F](https://fidoalliance.org/) دانگل (یک
[YubiKey](https://www.yubico.com/quiz/) برای مثال, که [برای دانشجویان 20% تخفیف دارد.](https://www.yubico.com/why-yubico/for-education/)). TOTP
(مثل Google Authenticator یا Duo) هم در شرایط اضطرار کار میکنند, اما
[شما را در برابر فیشینگ مقاوم نمیکنند.](https://twitter.com/taviso/status/1082015009348104192). پیام کوتاه هم تقریبا بی فایده
است، مگر اینکه مدل تحدید شما تنها شامل غریبه های اتفاقی باشد که کلمه عبور شما را در ترانزیت شنود میکنند.

همجنان, یک نکته راجب کلید های روی کاغذ. معمولا, سرویس ها
یک "کلید پشتیبان" به شما میدهند که میتوانید به ع
نوان مرحله دوم احراز هویت، در شرایطی که مرحله دوم
واقعی را از دست دادید استفاده کنید (در ضمن, همیشه یک دانگل پشتیبان
در یک جای امن نگاه دارید!). گرچه_میتوانید_ آنهارا هم در خود نرم ا
فزار مدیریت کلمه عبور ذخیره کنید, که یعنی اگر کسی به نرم افزار م
دیریت کلمه عبور دسترسی پیدا کند , همه چیز از دست خواهد رفت
(البته ممکن است شما با این مدل تحدید مشکلی نداشته باشید.). اگر حقیقتا پارانوئید هستید,
برگه های کلید را چاپ کنید, هیچ گاه دیجیتالی ذخیرشان نکنید, و
داخل یک گاو صندوق در دنیا واقعی نگهشان دارید.

## Private Communication

Use [Signal](https://www.signal.org/) ([setup
instructions](https://medium.com/@mshelton/signal-for-beginners-c6b44f76a1f0).
[Wire](https://wire.com/en/) is [fine
too](https://www.securemessagingapps.com/); WhatsApp is okay; [don't use
Telegram](https://twitter.com/bascule/status/897187286554628096)).
Desktop messengers are pretty broken (partially due to usually relying
on Electron, which is a huge trust stack).

E-mail is particularly problematic, even if PGP signed. It's not
generally forward-secure, and the key-distribution problem is pretty
severe. [keybase.io](https://keybase.io/) helps, and is useful for a
number of other reasons. Also, PGP keys are generally handled on desktop
computers, which is one of the least secure computing environments.
Relatedly, consider getting a Chromebook, or just work on a tablet with
a keyboard.

## File Security

File security is hard, and operates on many level. What is it you're
trying to secure against?

[![$5 wrench](https://imgs.xkcd.com/comics/security.png)](https://xkcd.com/538/)

- Offline attacks (someone steals your laptop while it's off): turn on
   full disk encryption. ([cryptsetup +
   LUKS](https://wiki.archlinux.org/index.php/Dm-crypt/Encrypting_a_non-root_file_system)
   on Linux,
   [BitLocker](https://fossbytes.com/enable-full-disk-encryption-windows-10/)
   on Windows, [FileVault](https://support.apple.com/en-us/HT204837) on
   macOS. Note that this won't help if the attacker _also_ has you and
   really wants your secrets.
- Online attacks (someone has your laptop and it's on): use file
   encryption. There are two primary mechanisms for doing so
  - Encrypted filesystems: stacked filesystem encryption software encrypts files individually rather than having encrypted block devices. You can "mount" these filesystems by providing the decryption key, and then browse the files inside it freely. When you unmount it, those files are all unavailable.  Modern solutions include [gocryptfs](https://github.com/rfjakob/gocryptfs) and [eCryptFS](http://ecryptfs.org/). More detailed comparisons can be found [here](https://nuetzlich.net/gocryptfs/comparison/) and [here](https://wiki.archlinux.org/index.php/disk_encryption#Comparison_table)
  - Encrypted files: encrypt individual files with symmetric
      encryption (see `gpg -c`) and a secret key. Or, like `pass`, also
      encrypt the key with your public key so only you can read it back
      later with your private key. Exact encryption settings matter a
      lot!
- [Plausible
   deniability](https://en.wikipedia.org/wiki/Plausible_deniability)
   (what seems to be the problem officer?): usually lower performance,
   and easier to lose data. Hard to actually prove that it provides
   [deniable
   encryption](https://en.wikipedia.org/wiki/Deniable_encryption)! See
   the [discussion
   here](https://security.stackexchange.com/questions/135846/is-plausible-deniability-actually-feasible-for-encrypted-volumes-disks),
   and then consider whether you may want to try
   [VeraCrypt](https://www.veracrypt.fr/en/Home.html) (the maintained
   fork of good ol' TrueCrypt).
- Encrypted backups: use [Tarsnap](https://www.tarsnap.com/) or [Borgbase](https://www.borgbase.com/)
  - Think about whether an attacker can delete your backups if they
      get a hold of your laptop!

## Internet Security & Privacy

The internet is a _very_ scary place. Open WiFi networks
[are](https://www.troyhunt.com/the-beginners-guide-to-breaking-website/)
[scary](https://www.troyhunt.com/talking-with-scott-hanselman-on/). Make
sure you delete them afterwards, otherwise your phone will happily
announce and re-connect to something with the same name later!

If you're ever on a network you don't trust, a VPN _may_ be worthwhile,
but keep in mind that you're trusting the VPN provider _a lot_. Do you
really trust them more than your ISP? If you truly want a VPN, use a
provider you're sure you trust, and you should probably pay for it. Or
set up [WireGuard](https://www.wireguard.com/) for yourself -- it's
[excellent](https://latacora.micro.blog/there-will-be/)!

{% comment %}
<https://raymii.org/s/blog/Cancellation_notice_for_cipherlist_ssldecoder_and_certificatemonitor.html>
cipherli.st and ssldecoder.org are cancelled
{% endcomment %}

If you're particularly privacy-oriented,
[privacytools.io](https://privacytools.io) is also a good resource.

Some of you may wonder about [Tor](https://www.torproject.org/). Keep in
mind that Tor is _not_ particularly resistant to powerful global
attackers, and is weak against traffic analysis attacks. It may be
useful for hiding traffic on a small scale, but won't really buy you all
that much in terms of privacy. You're better off using more secure
services in the first place (Signal, TLS + certificate pinning, etc.).

## Web Security

So, you want to go on the Web too?
Jeez, you're really pushing your luck here.

Install [HTTPS Everywhere](https://www.eff.org/https-everywhere).
SSL/TLS is
[critical](https://www.troyhunt.com/ssl-is-not-about-encryption/), and
it's _not_ just about encryption, but also about being able to verify
that you're talking to the right service in the first place! If you run
your own web server, [test it](https://www.ssllabs.com/ssltest/index.html). TLS configuration
[can get hairy](https://wiki.mozilla.org/Security/Server_Side_TLS).
HTTPS Everywhere will do its very best to never navigate you to HTTP
sites when there's an alternative. That doesn't save you, but it helps.
If you're truly paranoid, blacklist any SSL/TLS CAs that you don't
absolutely need.

Install [uBlock Origin](https://github.com/gorhill/uBlock). It is a
[wide-spectrum
blocker](https://github.com/gorhill/uBlock/wiki/Blocking-mode) that
doesn't just stop ads, but all sorts of third-party communication a page
may try to do. And inline scripts and such. If you're willing to spend
some time on configuration to make things work, go to [medium
mode](https://github.com/gorhill/uBlock/wiki/Blocking-mode:-medium-mode)
or even [hard
mode](https://github.com/gorhill/uBlock/wiki/Blocking-mode:-hard-mode).
Those _will_ make some sites not work until you've fiddled with the
settings enough, but will also significantly improve your online
security.

If you're using Firefox, enable [Multi-Account
Containers](https://support.mozilla.org/en-US/kb/containers). Create
separate containers for social networks, banking, shopping, etc. Firefox
will keep the cookies and other state for each of the containers totally
separate, so sites you visit in one container can't snoop on sensitive
data from the others. In Google Chrome, you can use [Chrome
Profiles](https://support.google.com/chrome/answer/2364824) to achieve
similar results.

Exercises

TODO

1. Encrypt a file using PGP
1. Use veracrypt to create a simple encrypted volume
1. Enable 2FA for your most data sensitive accounts i.e. GMail, Dropbox, Github, &c
