# myXNLI
Myanmar extension to XNLI Corpus

This project will add a Burmese (Myanmar) Corpus to the Cross Lingual NLI Corpus.
The original XNLI Corpus and paper can be found at https://github.com/facebookresearch/XNLI

## Myanmar Translation Instructions

Under `translation` folder, there are 100 files, each containing 100 blocks. Each block has a block number, an English sentence and a placeholder for Myanmar Translation.

For example:
```
114
We were watching something on TV.
<MYANMAR UNICODE TRANSLATION HERE>
```

As a translator, you can pick any file and add missing translations at the tag <MYANMAR UNICODE TRANSLATION HERE>, and keep other sentences intact. Please use only Myanmar Unicode font in your translations. You are also requested to separate Buremse phrases by spaces where it makes sense, and use ပုဒ်မ `။` as a sentence terminator.

After translation:
```
114
We were watching something on TV.
ကျွန်တော်တို့ တီဗီမှာ တခုခု ကြည့်နေခဲ့သည်။
```

 If you have been added to the project, you are welcome to directly update the translation files.
 If you are an external contributor, we welcome pull requests.