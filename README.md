## Malaysian Language Pack For [Flarum](https://discuss.flarum.org/d/3787-malaysian-language-pack-for-flarum)

Pakej Bahasa Malaysia untuk menyesuaikan [Flarum](http://flarum.sch.my/)

## Info
**Versi**: v0.1.0-beta.5 | **Syarat**: Flarum v0.1.0-beta.5 | **Kesesuaian**: Flarum v0.1.0-beta.5

 - Sudah diterjemahkan dengan sempurna.
 - Tiada yang belum diterjemahkan.

### Cara Pemasangan Utama
Jalankan `composer require ahrasis/flarum-ext-malaysian dev-master` di terminal ssh anda. Pastikan anda berada pada dasar laman web flarum anda. Tunggu sehingga selesai. Masuk ke panel kawalan admin flarum, klik **Extensions**, aktifkan Bahasa Malaysia. ;)

### Cara Pemasangan Alternatif
1. [Muatturun](https://github.com/ahrasis/flarum-ext-malaysian/archive/master.zip).
2. Ekstrak dan muatnaik ke dalam folder **vendor\ahrasis**.
3. Ubah nama folder **flarum-ext-malaysian-master** menjadi **flarum-ext-malaysian**.
4. Buka fail **vendor\composer\installed.json** dan tambahkan ini:
`     {
        "name": "ahrasis/flarum-ext-malaysian",
        "version": "v0.1.0-beta.8",
        "version_normalized": "0.1.0-beta.8-dev",
        "source": {
            "type": "git",
            "url": "https://github.com/ahrasis/flarum-ext-malaysian.git",
            "reference": "964ad5b7223dbef387e9c0ad5f78c41a8c909a33"
        },
        "dist": {
            "type": "zip",
            "url": "https://api.github.com/repos/ahrasis/flarum-ext-malaysian/zipball/964ad5b7223dbef387e9c0ad5f78c41a8c909a33",
            "reference": "964ad5b7223dbef387e9c0ad5f78c41a8c909a33",
            "shasum": ""
        },
        "require": {
            "flarum/core": "^0.1.0-beta.8"
        },
        "type": "flarum-extension",
        "extra": {
            "flarum-extension": {
                "title": "Bahasa Malaysia",
                "icon": {
                    "image": "icon.svg",
                    "backgroundColor": "#00247d",
                    "backgroundSize": "cover",
                    "backgroundPosition": "center"
                }
            },
            "flarum-locale": {
                "code": "my",
                "title": "Bahasa Malaysia"
            }
        },
        "installation-source": "source",
        "notification-url": "https://packagist.org/downloads/",
        "license": [
            "MIT"
        ],
        "authors": [
            {
                "name": "Hj Ahmad Rasyid Hj Ismail",
                "email": "ahrasis@gmail.com"
            }
        ],
        "description": "Pakej Bahasa Malaysia",
        "keywords": [
            "locale"
        ]
    }`
5. Masuk ke panel kawalan admin Flarum, klik **Extensions**.
6. Aktifkan.

### Lesen
Disediakan di bawah lesen MIT. Sila semak fail [lesen](https://github.com/ahrasis/flarum-ext-malaysian/blob/master/LICENSE).

