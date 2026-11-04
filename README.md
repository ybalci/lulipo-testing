# Lulipo: Match & Pop — Android testing / Android testi

![Lulipo](lulipo-icon-512.png)

**[Open the optional APK test hub / APK test sayfası](https://ybalci.github.io/lulipo-testing/)**

Help improve Lulipo by playing naturally and reporting what you actually observe. This is a voluntary test; no positive rating, review, or purchase is required.

## Download the current APK

**[Download Lulipo 0.7.2-test for Android](https://github.com/ybalci/lulipo-testing/releases/download/v0.7.2-test/Lulipo-Android-0.7.2-Fair-Test.apk)** · Android 7.0 or later · about 6.6 MB.

Use this repository's release assets only. The [release page](https://github.com/ybalci/lulipo-testing/releases/tag/v0.7.2-test) includes release notes and SHA-256 checksums. No GitHub account is needed to download the public APK.

1. Download on your Android phone and open the APK.
2. If Android asks, allow installation from the browser or file manager you used.
3. Install **Lulipo · Test**. You can turn that installation permission off afterwards.
4. Choose Turkish/English and Easy/Normal/Hard on the home screen.

This APK uses the existing development test identity (com.mahalle.esles.test). Compatible earlier test installs can be updated. It is separate from the Google Play package (com.lulipogames.lulipo); it does not become a Play installation.

## Google Play closed test

The Google Play opt-in link is **being prepared and is not live yet**. It will be shared separately when the track is ready. GitHub is not required for the Google Play test.

**Downloading or installing this GitHub APK does not enroll you in Google Play's closed test and does not count toward its 12-testers / 14-days requirement.** When the Play link is available, join using your invited Google account and install from Google Play. Genuine play and feedback are welcome; do not leave an inflated rating or scripted review.

## What changed in 0.7.2

- Choose **Easy, Normal or Hard** before starting.
- Easy: 120 seconds and more moves; Normal: 90 seconds; Hard: 75 seconds with the same baseline move allowance as Normal.
- Before a new board opens, the game checks a winning path that completes color targets, the ice quota and locks without ads, purchases or boosters, with at least two initial moves spare.
- If a generated board cannot be certified within the bounded search, a verified board is used. Certified board families can repeat. This does **not** guarantee a human finishes within the timer or wins after mistakes.
- Language and difficulty preferences are remembered locally; a new game session begins at level 1.
- A local English/Turkish privacy page is included.
- Ads and purchases are explicitly **demos**. No real ad is shown and no payment is charged in this test release.
- The Android game is bundled for offline use and does not require a player account.

## Feedback

Use **[Issues → New issue](https://github.com/ybalci/lulipo-testing/issues/new/choose)** or email **[yavuz@presult.com.tr](mailto:yavuz@presult.com.tr)**. A GitHub account is required to create an issue; email is an alternative.

Include phone model, Android version, game version, chosen difficulty, reproduction steps, expected/actual behavior, and an optional screenshot. **Do not post passwords, authentication codes, private email addresses or other sensitive personal information in public issues.**

See the [test guide / test rehberi](TESTING.md) and [privacy policy / gizlilik politikası](https://ybalci.github.io/lulipo-testing/privacy.html).

---

## Türkçe

Lulipo'nun Android testine katılıp oyunu doğal şekilde oynayarak geliştirmemize yardımcı olabilirsin. **Olumlu puan, yorum veya satın alma şartı yok.**

- **[İsteğe bağlı APK test sayfası](https://ybalci.github.io/lulipo-testing/)** üzerinden güncel APK'yı indir veya hata bildir.
- Ana ekranda **Basit / Orta / Zor** seç. Basit 120 sn, Orta 90 sn, Zor 75 sn sürer. Zor mod, Orta ile aynı temel hamle hakkını korur.
- Tahtalar, hedefleri en az iki hamle payıyla tamamlayan bir yol için denetlenir. Doğrulanamayan aday yerine doğrulanmış tahta kullanılır; tahta aileleri tekrar edebilir. Sürede yetişme ve hatasız oynama garantisi verilmez.
- Buz/kilit hedeflerini, dokunmayı, sesleri, dili, duraklatmayı ve uygulamayı kapatıp açmayı test et.
- Reklam ve satın almalar demodur; gerçek reklam gösterimi veya ücret yoktur.
- **GitHub APK kurulumu, Google Play kapalı testine katılım sayılmaz.** Play bağlantısı hazır olduğunda ayrıca kayıt olup Play'den yüklemek gerekecek; GitHub hesabı gerekmez.

## Repository scope

This public repository contains tester documentation, promotional images, a static test/privacy website and APK releases. It does not distribute the game's source code, signing keys, credentials, AAB upload bundles or licensed raw sound assets. No open-source license is granted for the game or its media.
