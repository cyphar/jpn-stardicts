## Japanese StarDicts ##

StarDict is not a common format for Japanese dictionaries, but a lot of ereader
programs (many of which cannot handle Japanese verb inflection and text
segmentation, making word lookups quite difficult) use StarDict, so this is a
mirror of existing resource on GitHub so that they can be fetched more easily.

Each of the following dictionaries has "synonym-based deinflection" meaning
that if your ereader cannot handle Japanese inflection (which is probably the
case -- unless you use [KOReader][koreader]) you can still look up inflected
verbs by searching using only the verb stem.

For instance to look up "偲ぶ" from the text "偲んでる" select the verb up to
and including the first 送り仮名 (okurigana) character -- "偲ん" and search for
that, which will give you the results for "偲ぶ". The same goes for any verb or
i-adjective (for 五段/godan/ru-verbs the stem obviously won't have any
okurigana -- for "見えない" just select "見"). The way this works internally is
that for every inflectible word, a set of synonyms is included for every
possible inflection stem.

[koreader]: https://koreader.rocks/

#### Bilingual (Japanese-English) ###

These dictionaries were converted by epistularum(エピス)#9370.

 * JMdict ([download][jmdict-download]) is probably the most well-known
   general-purpose Japanese-English dictionary available. It is freely licensed
   (CC BY-SA 3.0) with the copyrights held by the The Electronic Dictionary
   Research and Development Group. You can find more information [on their
   wiki][jmdict-wiki].

 * JMnedict ([download][jmnedict-download]) is a special-purpose dictionary
   only containing Japanese names. It is a separate part of the larger
   JMdict-EDICT project, and is copyrighted by the same entity and released
   under the same license (CC BY-SA 3.0). You can find more information [on
   their website][jmnedict-web].

[jmdict-download]: https://cyphar.github.io/jpn-stardicts/JMdict-ja-en.tar.gz
[jmnedict-download]: https://cyphar.github.io/jpn-stardicts/JMnedict-ja-en.tar.gz

[jmdict-wiki]: http://www.edrdg.org/wiki/index.php/JMdict-EDICT_Dictionary_Project
[jmnedict-web]: http://www.edrdg.org/enamdict/enamdict_doc.html
