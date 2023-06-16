<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Woɖo aɖaŋu be nàde nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) gbã, eye emegbe `direnv allow` ne ège ɖe agbalẽdzraɖoƒea vɔ ( [.envrc la](https://github.com/xxai-art/doc/blob/main/.envrc) awɔ dɔ le eɖokui si ne ège ɖe agbalẽdzraɖoƒea vɔ).

Gɔmeseseae nye: Chinagbe gɔmeɖeɖe ɖe Japangbe, Koreagbe, Eŋlisigbe, Eŋlisigbe me gɔmeɖeɖe ɖe gbe bubuwo katã me. Ne Chinagbe kple Eŋlisigbe koe nèdi be yeado alɔe la, àte ŋu aŋlɔ `zh: en` .

Gɔmeseseae nye: Chinagbe gɔmeɖeɖe ɖe Japangbe, Koreagbe, Eŋlisigbe, Eŋlisigbe me gɔmeɖeɖe ɖe gbe bubuwo katã me. Ne Chinagbe kple Eŋlisigbe koe nèdi be yeado alɔe la, àte ŋu aŋlɔ `zh: en` .

* [ŋgɔgbe-nuwuwu ƒe kɔpi](https://github.com/xxai-art/web)
* [Gbegbɔgblɔ ƒe agbalẽviwo na nyatakakadzraɖoƒe bliboa](https://github.com/xxai-art/web/tree/main/i18n)
* [Gbegbɔgblɔ ƒe agbalẽviwo na gegeɖe modules](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Nyatakakadzraɖoƒe ƒe Gbegbɔgblɔ Vovovowo me Nuŋlɔɖiwo](https://github.com/xxai-doc)

Dɔwɔɖoɖo ƒe gbegbɔgblɔ si le ŋgɔgbe enye [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , si tsɔ nɔnɔme aɖewo kpe ɖe eŋu si wotu ɖe coffeescript ƒe nyagɔmeɖegbalẽ dzi, kpɔ [./coffee_plus.md](./coffee_plus.md) .

## Nyatakakadzraɖoƒewo kple nuŋlɔɖiwo ƒe dukɔwo dome wɔwɔ

Tu ɖe dɔ 3 siwo gbɔna dzi

* [@w5/mdt ƒe nyawo](https://www.npmjs.com/package/@w5/mdt)

  Megbenya la nye `.mdt` , àteŋu azã nyagɔmeɖegbalẽ si sɔ kple `<+ ./coffee_plus/import.js>` atsɔ aƒo nu tso gotagome faɛlwo ŋu, eye nàwɔ markdown kple megbenya `.md` .

* [@w5/trmd ƒe nyawo](https://www.npmjs.com/package/@w5/trmd)

  Markdown gɔmeɖeɖe maɖe kɔdawo kple kadodowo gɔme o, eye wòatsɔ nyagbe siwo gɔme woɖe la adzra ɖo. Ne wotrɔ asi le gɔmeɖeɖea ŋu gake wometrɔ asi le nuŋɔŋlɔ gbãtɔa ŋu o la, ewɔwɔ ake maŋlɔ tɔtrɔ si wowɔ le gɔmeɖeɖea ŋu o.

* [@w5/i18n ƒe nyawo](https://www.npmjs.com/package/@w5/i18n)

  Gbegbɔgblɔ ƒe faɛlwo hena nyatakakadzraɖoƒe siwo `yaml` wɔ la gɔmeɖeɖe.

### Document Translation Automation Mɔfiamewo

Kpɔ kɔdawo ƒe nudzraɖoƒe [xxai-art/doc](https://github.com/xxai-art/doc)

Woɖo aɖaŋu be nàde nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) gbã, eye emegbe `direnv allow` ne ège ɖe agbalẽdzraɖoƒea vɔ ( [.envrc la](https://github.com/xxai-art/doc/blob/main/.envrc) awɔ dɔ le eɖokui si ne ège ɖe agbalẽdzraɖoƒea vɔ).

Be maƒo asa na kɔda gã si gɔme woɖe ɖe gbegbɔgblɔ alafa geɖe me la, mewɔ kɔda ƒe gɔmeɖoanyi ɖe vovo na gbegbɔgblɔ ɖesiaɖe eye mewɔ habɔbɔ aɖe si adzra kɔdaɖoɖoa ɖo

Ne èɖo nutome ƒe tɔtrɔ `GITHUB_ACCESS_TOKEN` eye emegbe nèwɔ [create.github.coffee la](https://github.com/xxai-art/doc/blob/main/create.github.coffee) , awɔ kɔda ƒe nudzraɖoƒea le eɖokui si.

Nyateƒee, àte ŋu atsɔe ade code base hã me.

Gbegɔmeɖeɖe ŋɔŋlɔdzesi ƒe nufiame [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Woɖe ŋɔŋlɔdzesi ƒe kɔpi gɔme ale:

[bunx](https://bun.sh/docs/cli/bunx) nye npx teƒenɔla, si le kabakaba wu. Nyateƒee, ne bun mele asiwò o la, àte ŋu azã `npx` ɖe eteƒe.

`bunx mdt zh` ɖea `.mdt` le zh ƒe nuŋlɔɖi me abe `.md` ene, kpɔ faɛl 2 siwo do ƒome kplii le ete

* [kɔfi_tsɔ kpe ɖe eŋu.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [kɔfi_tsɔ kpe ɖe eŋu.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` nye gɔmeɖeɖe ƒe kɔda vevitɔ (ne `nodejs` koe le asiwò, gake womede `bun` kple `direnv` o la, àteŋu awɔ `npx i18n` hã atsɔ aɖe gbegɔme).

Aɖe [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) me, `i18n.yml` ƒe ɖoɖowɔwɔ le nuŋlɔɖi sia me le ale:

```
en:
zh: ja ko en
```

Gɔmeseseae nye: Chinagbe gɔmeɖeɖe ɖe Japangbe, Koreagbe, Eŋlisigbe, Eŋlisigbe me gɔmeɖeɖe ɖe gbe bubuwo katã me. Ne Chinagbe kple Eŋlisigbe koe nèdi be yeado alɔe la, àte ŋu aŋlɔ `zh: en` .

Mlɔetɔ enye [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , si ɖea nusiwo le gbegbɔgblɔ ɖesiaɖe ƒe `README.md` ƒe tanya vevitɔ kple tanya sue gbãtɔ dome tsɔ wɔa nya aɖe si woŋlɔ ɖe `README.md` . Code la le bɔbɔe ŋutɔ, wò ŋutɔ àte ŋu alé ŋku ɖe eŋu.

Wozãa Google API hena gbegɔmeɖeɖe femaxee. Ne màte ŋu age ɖe Google me o la, taflatse wɔ ɖoɖo eye nàɖo proxy, abe:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Gbegɔmeɖeɖe ŋɔŋlɔdzesi la awɔ cache si gɔme woɖe le `.i18n` directory me, taflatse lé ŋku ɖe eŋu kple `git status` eye nàtsɔe akpe ɖe code nudzraɖoƒea ŋu be nàƒo asa na gbegɔmeɖeɖe enuenu.

Taflatse ƒu du `bunx i18n` ɣesiaɣi si nètrɔ asi le gbegɔmeɖeɖea ŋu be nàwɔ cache la yeyee.

Ne wotrɔ asi le nuŋɔŋlɔ gbãtɔ kple gɔmeɖeɖea ŋu le ɣeyiɣi ɖeka me la, cache la atɔtɔ, eyata ne èdi be yeatrɔ asi le eŋu la, ɖeka koe nàte ŋu atrɔ, eye emegbe nàwɔ `bunx i18n` atsɔ awɔ cache la yeyee.
