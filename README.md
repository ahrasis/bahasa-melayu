## Malaysian Language Pack For [Flarum](http://flarum.org/)

Pakej Bahasa Malaysia untuk menyesuaikan [Flarum](http://flarum.org/)

## Info
**Versi**:  1.0.0-dev | **Syarat**: Flarum 0.1.0 Beta 5 | **Kesesuaian**: Flarum 0.1.0 Beta 5

 - Sudah diterjemahkan dengan sempurna.
 - Tiada yang belum diterjemahkan.

### Cara
1. [Muatturun](https://github.com/ahrasis/flarum-ext-malaysian/archive/master.zip).
2. Ekstrak dan muatnaik ke dalam folder **vendor\flarum**.
3. Ubah nama folder **flarum-ext-malaysian-master** menjadi **flarum-ext-malaysian**.
4. Buka fail **vendor\composer\installed.json** dan tambahkan ini:

`    {
        "name": "flarum/flarum-ext-malaysian",
        "version": "v1.0.0-dev",
        "require": {
            "flarum/core": "^0.1.0-beta.5"
        },
        "type": "flarum-extension",
        "extra": {
            "branch-alias": {
                "dev-master": "0.1.x-dev"
            },
            "flarum-extension": {
                "title": "Malaysia",
                "icon": {
                    "image": "icon.svg",
                    "backgroundColor": "#00247d",
                    "backgroundSize": "cover",
                    "backgroundPosition": "center"
                }
            },
            "flarum-locale": {
                "code": "my",
                "title": "Malaysia"
            }
        },
        "license": [
            "MIT"
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

