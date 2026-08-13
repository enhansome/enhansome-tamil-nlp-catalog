# Tamil Deep Learning Awesome List with stars

> A curated catalog of open-source resources for Tamil NLP & AI.

<img src="https://1.bp.blogspot.com/-jImAZD8-kIY/WhwLddVQ0FI/AAAAAAAABmY/cW7pjolPoS4KGb3iXrxikDBgWL3VLAqpwCEwYBhgL/s1600/A%2Btamil%2Btypo%2Bnw.jpg" height="400px" />

The estimated worldwide Tamiḻ-speaking population is around 80-85 million, which is near to the population of Germany. Hence it is crucial to work on natural language processing for தமிழ் (Tamiḻ) and develop tools inorder to ensure the language is digitally well-represented.

This list will serve as a catalog for all resources related to Tamil NLP.

Note:

* *Please use [GitHub Issues](https://github.com/narVidhai/tamil-nlp-catalog/issues) ⭐ 118 | 🐛 4 | 🌐 HTML | 📅 2023-04-06 for queries/feedback or to **contribute** resources/links.*
* *If you find this useful, please [star this on GitHub](https://github.com/narVidhai/tamil-nlp-catalog) ⭐ 118 | 🐛 4 | 🌐 HTML | 📅 2023-04-06 to encourage this list to be active.*
  * If you want to follow all latest updates in this catalog, press "watch" button on top-right of this repo.
* *Share this [awesome website](https://narvidhai.github.io/tamil-nlp-catalog) if you liked it! :-)*

<div id="toc-container">
<hr/>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

## Table of Contents <!-- {docsify-ignore} -->

* [**Tools, Libraries, Models**](#tools-libraries-models)
  * [General](#general)
  * [Word Embeddings](#word-embeddings)
  * [Transformers, BERT](#transformers-bert)
  * [Translation](#translation)
    * [Online translation libraries](#online-translation-libraries)
  * [Transliteration](#transliteration)
  * [OCR](#ocr)
  * [Speech](#speech)
  * [Grammar](#grammar)
  * [Miscellaneous](#miscellaneous)
* [**Datasets**](#datasets)
  * [Monolingual Corpus](#monolingual-corpus)
    * [Government Raw Text](#government-raw-text)
  * [Translation](#translation-1)
    * [Government parallel data](#government-parallel-data)
    * [Papers](#papers)
  * [Transliteration](#transliteration-1)
  * [Speech, Audio](#speech-audio)
    * [Speech-To-Text](#speech-to-text)
    * [Speech Translation](#speech-translation)
    * [Text-to-Speech (TTS)](#text-to-speech-tts)
    * [Audio](#audio)
  * [Named Entity Recognition](#named-entity-recognition)
  * [Text Classification](#text-classification)
  * [OCR](#ocr-1)
    * [Character-level datasets](#character-level-datasets)
    * [Scene-Text Detection / Recognition](#scene-text-detection--recognition)
    * [Document OCR](#document-ocr)
  * [Part-Of-Speech (POS) Tagging](#part-of-speech-pos-tagging)
  * [Sentiment and Abuse Analysis](#sentiment-and-abuse-analysis)
  * [Lexical Resources](#lexical-resources)
  * [Natural Language Generation](#natural-language-generation)
  * [Benchmarks](#benchmarks)
  * [Miscellaneous NLP Datasets](#miscellaneous-nlp-datasets)
* [**Other Important Resources**](#other-important-resources)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

</div>

<hr/>

## **Tools, Libraries, Models**

### General

* [iNLTK](https://inltk.readthedocs.io/) (Tools for processing and trained models)
* [Indic NLP Library](http://anoopkunchukuttan.github.io/indic_nlp_library/) (Script-processing tools)

Also check Ezhil Foundation's [Awesome-Tamil](https://github.com/Ezhil-Language-Foundation/awesome-tamil) ⭐ 11 | 🐛 0 | 📅 2024-03-03 for lot more resources!

### Word Embeddings

* [Facebook MUSE](https://github.com/facebookresearch/MUSE) ⚠️ Archived
* [ConceptNet](https://github.com/commonsense/conceptnet-numberbatch) ⭐ 1,322 | 🐛 10 | 🌐 Python | 📅 2022-07-18
* [GeoMM](https://github.com/anoopkunchukuttan/geomm) ⭐ 27 | 🐛 30 | 🌐 Python | 📅 2022-12-08
* FastText
  * [Multilingual Aligned](https://github.com/babylonhealth/fastText_multilingual) ⭐ 1,201 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2023-03-10 - {2017}
  * [Wikipedia-based](https://fasttext.cc/docs/en/pretrained-vectors.html) - {2016}
  * [CommonCrawl+Wikipedia](https://fasttext.cc/docs/en/crawl-vectors.html) - {2017}
  * [AI4Bharat IndicFT](https://indicnlp.ai4bharat.org/indicft) - {2020}
* [BPEmb: Subword Embeddings](https://nlp.h-its.org/bpemb/) - {2017, [Aligned Multilingual](https://nlp.h-its.org/bpemb/multi/)}
* [PolyGlot](https://sites.google.com/site/rmyeid/projects/polyglot)

### Transformers, BERT

* [Multilingual BERT](https://github.com/google-research/bert/blob/master/multilingual.md) ⚠️ Archived
* [Google Multilingual T5](https://github.com/google-research/multilingual-t5) ⚠️ Archived, [mT6 and DeltaLM](https://github.com/microsoft/unilm/tree/master/deltalm) ⭐ 22,186 | 🐛 684 | 🌐 Python | 📅 2026-01-23
* [TranKit](https://github.com/nlp-uoregon/trankit) ⭐ 795 | 🐛 40 | 🌐 Python | 📅 2025-07-22
* [Multilingual Text2Text](https://github.com/artitw/text2text) ⭐ 304 | 🐛 28 | 🌐 Python | 📅 2025-01-14
* iNLTK (ULMFit and TransformerXL) - [Tamil](https://github.com/goru001/nlp-for-tamil) ⭐ 52 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-08-07 | [Tanglish](https://github.com/goru001/nlp-for-tanglish) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-03-07
* AI4Bharat: [ALBERT](https://indicnlp.ai4bharat.org/indic-bert), [BART](https://github.com/AI4Bharat/indic-bart) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2022-07-20
* [XML RoBERTa](https://huggingface.co/transformers/model_doc/xlmroberta.html)
* [Google ELECTRA - TaMillion](https://huggingface.co/monsoon-nlp/tamillion) - {2020, [Code](https://mapmeld.medium.com/training-bangla-and-tamil-language-bert-models-46d7262b550f)}
* Google MuRIL - {2020, [TF-Hub](https://tfhub.dev/google/MuRIL/1), [HuggingFace](https://huggingface.co/google/muril-base-cased)}

### Translation

* NMT
  * [AI4Bharat IndicTrans](https://indicnlp.ai4bharat.org/indic-trans/) - {2021, [Paper](https://arxiv.org/abs/2104.05596)}
  * [not-AI-Tech Anuvaad](https://github.com/notAI-tech/Anuvaad) ⭐ 4 | 🐛 3 | 🌐 Python | 📅 2021-04-11 - {2020, mT5 model fine-tuned on public datasets}
  * [IIIT-H IndicMulti](https://github.com/jerinphilip/ilmulti) ⭐ 22 | 🐛 5 | 🌐 Python | 📅 2022-03-05
  * [EasyNMT](https://github.com/UKPLab/EasyNMT) ⭐ 1,261 | 🐛 55 | 🌐 Python | 📅 2023-12-21 - Collection of open source multilingual NMT models
* Moses SMT
  * [IIT-B Śata-Anuva̅dak](http://www.cfilt.iitb.ac.in/~moses/shata_anuvaadak/)

#### Online translation libraries

* [Python Translators](https://github.com/UlionTse/translators) ⭐ 2,704 | 🐛 10 | 🌐 Python | 📅 2026-01-26

### Transliteration

* [Word Phonemizer](https://github.com/bootphon/phonemizer) ⭐ 1,566 | 🐛 37 | 🌐 Python | 📅 2026-08-04
* LibIndic - [Rule-based and Model-based](https://github.com/libindic/indic-trans) ⭐ 275 | 🐛 18 | 🌐 Python | 📅 2022-10-28 | [English words](https://github.com/libindic/Transliteration) ⭐ 79 | 🐛 7 | 🌐 Roff | 📅 2025-10-24
* [Indic Transliteration](https://github.com/sanskrit-coders/indic_transliteration) ⭐ 210 | 🐛 8 | 🌐 Python | 📅 2026-08-02
* [notAI.tech DeepTranslit](https://github.com/notAI-tech/DeepTranslit) ⚠️ Archived
* [AI4Bharat Xlit](https://pypi.org/project/ai4bharat-transliteration/)
* [AksharaMukha](http://aksharamukha.appspot.com/converter) - [API](http://aksharamukha.appspot.com/python)
* [PolyGlot Transliteration](https://polyglot.readthedocs.io/en/latest/Transliteration.html)
* [EpiTran](https://pypi.org/project/epitran/) - IPA Transliteration
* [WikTra](https://twardoch.github.io/wiktra2/) - Tamil Romanizer

### OCR

* [Tesseract](https://indic-ocr.github.io/tessdata/)
* [EasyOCR](https://www.jaided.ai/easyocr)

### Speech

* [Coqui](https://coqui.ai/tamil/itml/v0.1.0#download) - [StT](https://github.com/coqui-ai/STT) ⭐ 2,604 | 🐛 106 | 🌐 C++ | 📅 2024-03-11
* [Vākyānsh ASR](https://github.com/Open-Speech-EkStep/vakyansh-models) ⭐ 327 | 🐛 8 | 📅 2022-09-16
* [IIT-M TTS](https://github.com/tshrinivasan/tamil-tts-install) ⭐ 31 | 🐛 1 | 🌐 Shell | 📅 2018-09-12
* [VasuRobo Speech Recognizer](https://github.com/vasurobo/tamil-speech-recognition) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2019-12-04
* [Indic Wav2Vec2](https://indicnlp.ai4bharat.org/indicwav2vec/)

### Grammar

* [Google Nisaba (Text Processing Grammar)](https://github.com/google-research/nisaba/blob/main/nisaba/brahmic/README.md) ⭐ 52 | 🐛 32 | 🌐 Python | 📅 2026-07-28
* [Tamil Prosody (யாப்பிலக்கணம்) Analyzer](https://github.com/virtualvinodh/avalokitam) ⭐ 29 | 🐛 3 | 🌐 Vue | 📅 2026-06-25

### Miscellaneous

* [Indic POS Tagger](https://github.com/avineshpvs/indic_tagger) ⭐ 46 | 🐛 9 | 🌐 Python | 📅 2023-02-02
* [Number To Words](https://github.com/sutariyaraj/indic-num2words) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2025-05-23
* [Tamilinaiya Spell Checker](https://github.com/tshrinivasan/Tamilinaiya-Spellchecker) ⭐ 8 | 🐛 1 | 🌐 C# | 📅 2023-10-19
* [Punctuation Restoration](https://github.com/VarnithChordia/Multlingual_Punctuation_restoration) ⭐ 7 | 🐛 9 | 🌐 Python | 📅 2022-12-13 & [Indic-Punct](https://github.com/Open-Speech-EkStep/indic-punct) ⭐ 45 | 🐛 5 | 🌐 Python | 📅 2022-12-15
* [Tamil Language Model and Tokenizer](https://github.com/ravi-annaswamy/tamil_lm_spm_fai) ⭐ 3 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-03-30 - {2018}

***

## **Datasets**

### Monolingual Corpus

* CommonCrawl
  * [OSCAR Corpus 2019](https://oscar-corpus.com/) - Deduplicated Corpus {226M Tokens, 5.1GB)
  * [WMT Raw 2017](http://data.statmt.org/ngrams/raw/) - CC crawls from 2012-2016
  * [CC-100](http://data.statmt.org/cc-100/) - CC crawls from Jan-Dec 2018
* [AI4Bharat IndicCorp](https://indicnlp.ai4bharat.org/corpora/) - {582M}
* [WikiDumps](https://dumps.wikimedia.org/tawiki/)
* [WMT News Crawl](http://data.statmt.org/news-crawl/ta/)
* [Kaggle Tamil Articles Corpus](https://www.kaggle.com/praveengovi/tamil-language-corpus-for-nlp)
* [Dinamalar News Corpus](https://www.kaggle.com/vijayabhaskar96/tamil-news-dataset-19-million-records) - {2009-19, 120k articles}
* [TamilMurasu News Articles](https://www.kaggle.com/vijayabhaskar96/tamil-news-classification-dataset-tamilmurasu) - {2011-19, 127k articles}
* [Leipzig Corpora](https://wortschatz.uni-leipzig.de/en/download/tamil)
* [Cholloadai, 2021](https://github.com/vanangamudi/cholloadai-2021) ⭐ 4 | 🐛 0 | 📅 2021-12-06 - 72M phrases (not sentences)

#### Government Raw Text

* [LDCIL Standard Text Corpus](https://data.ldcil.org/a-gold-standard-tamil-raw-text-corpus) - Free for students/faculties {11M tokens}
* [EMILLE Corpus](http://www.emille.lancs.ac.uk/) - {20M Tokens, developed [in collaboration with CIIL](http://corpora.ciil.org/)}
* [Project Madurai](https://www.projectmadurai.org/pmworks.html)

### Translation

* [Tatoeba Wiki Back-translated data](https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/Backtranslations.md) ⭐ 852 | 🐛 12 | 🌐 Makefile | 📅 2024-08-20
* [MTurks Crowd-sourced](https://github.com/joshua-decoder/indian-parallel-corpora) ⭐ 70 | 🐛 0 | 🌐 OCaml | 📅 2023-06-29 - {2012}
* [IndoWordNet](https://github.com/anoopkunchukuttan/indowordnet_parallel) ⭐ 8 | 🐛 1 | 📅 2020-06-16
* [AI4Bharat Samān-Antar](https://indicnlp.ai4bharat.org/samanantar/) {[Paper](https://arxiv.org/abs/2104.05596)}
  * Contains most open source datasets also as of March 2021
* [OPUS Corpus](http://opus.nlpl.eu/) (Search en->ta)
  * Note: CC-Aligned overlaps with [CommonCrawl-Matrix](https://github.com/facebookresearch/LASER/tree/master/tasks/CCMatrix) ⚠️ Archived
  * Contains [MultiCC Aligned](http://statmt.org/cc-aligned/), [JW300](https://opus.nlpl.eu/JW300-v1.php), [Tanzil](https://opus.nlpl.eu/Tanzil.php), [bible-corpus](https://github.com/christos-c/bible-corpus) ⭐ 197 | 🐛 3 | 📅 2025-05-19, [WikiMatrix](https://github.com/facebookresearch/LASER/tree/master/tasks/WikiMatrix) ⚠️ Archived, and more...
* [MultiIndicMT - WAT2021](http://lotus.kuee.kyoto-u.ac.jp/WAT/indic-multilingual/index.html) / [WMT20 NEWS MT Task](http://www.statmt.org/wmt20/translation-task.html#download)
  * Contains [PM India Corpus](http://data.statmt.org/pmindia), [Manathin Kural (CVIT-MkB)](http://preon.iiit.ac.in/~jerin/bhasha/), [NLPC-UoM Corpus](https://github.com/nlpc-uom/English-Tamil-Parallel-Corpus) ⭐ 14 | 🐛 1 | 📅 2021-01-04, [Wiki Titles](http://data.statmt.org/wikititles/v2/wikititles-v2.ta-en.tsv.gz), [Charles University EnTam v2.0 Corpus](http://ufal.mff.cuni.cz/~ramasamy/parallel/html/)
* EkStep Anuvaad
  * [Parallel Corpora](https://github.com/project-anuvaad/anuvaad-parallel-corpus) ⭐ 24 | 🐛 1 | 📅 2022-05-05
  * [Synthetic Corpus](https://github.com/project-anuvaad/parallel-corpus) - Translations generated using Google
* [VPT-IL-FIRE2018](http://78.46.86.133/VPT-IL-FIRE2018/) - 3k verb phrases, available on request

Note: You can also use the [MTData library](https://pypi.org/project/mtdata/) to automatically download parallel data from many of the above sources.

#### Government parallel data

* [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp) - Available only on request
* TDIL EILMT
  * [Tourism](http://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1422\&lang=en), [Agriculture](http://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1801\&lang=en), [Health](http://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1789\&lang=en)
  * Mirrored at [NPLT](https://nplt.in/demo/index.php?route=product/category\&path=75_59\&limit=100)
* Hindi-Tamil ILCI
  * [Parallel Chunked Text Corpus ILCI-II](https://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=2067\&lang=en), [Tourism Text Corpus](https://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1411), [Agriculture & Entertainment Text Corpus-ILCI II](https://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1675), [General Text Corpus](https://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1271), [Health Text Corpus](https://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1394)
* [Telugu-Tamil General Text Corpus](https://tdil-dc.in/index.php?option=com_download\&task=showresourceDetails\&toolid=1570)

#### Papers

* [Sinhala-Tamil Parallel Corpus](https://ucsc.cmb.ac.lk/machine-translation-system-sinhala-tamil-language-pair/) - {[Paper1](https://www.aclweb.org/anthology/U14-1018/), [Paper2](https://ieeexplore.ieee.org/document/7980522), Data available on request?, [Test set](https://github.com/nlpc-uom/Sinhala-Tamil-Aligned-Parallel-Corpus) ⭐ 3 | 🐛 0 | 📅 2019-05-29}
* [MIDAS-NMT, 2018](https://github.com/precog-iiitd/MIDAS-NMT-English-Tamil) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2018-09-01 - Uses OPUS+EnTam data
* [cEnTam: Creation of a New English-Tamil Corpus, 2020](https://www.aclweb.org/anthology/2020.bucc-1.10.pdf) - Uses OPUS+WMT20 data

### Transliteration

* [Google Dakshina Dataset](https://github.com/google-research-datasets/dakshina) ⚠️ Archived
* [TRANSLIT: A Large-scale Name Transliteration Resource](https://github.com/fbenites/TRANSLIT) ⭐ 7 | 🐛 7 | 🌐 Python | 📅 2022-12-08 - {2020, [Paper](https://www.aclweb.org/anthology/2020.lrec-1.399.pdf)}
* [Microsoft Multi-Indic Mined Corpus](https://github.com/anoopkunchukuttan/indic_transliteration_analysis) ⭐ 1 | 🐛 1 | 📅 2021-04-09 - {2021, [Paper](https://www.aclweb.org/anthology/2021.eacl-main.303/)}
* [Thirukkural Transliteration](https://github.com/narVidhai/Thirukkural-transliteration-data) ⭐ 0 | 🐛 0 | 📅 2020-11-20 (Old Tamil)
* [NEWS2018 Dataset](http://workshop.colips.org/news2018/dataset.html)
* [ICTA English-Sinhala-Tamil Names](https://www.language.lk/en/resources/code-resources/) - {2009, 10k triplets, SQL format}

### Speech, Audio

#### Speech-To-Text

* [Facebook CoVoST](https://github.com/facebookresearch/covost) ⚠️ Archived - {2019, 2-4 hours}
* [Ek-Step ULCA ASR dataset](https://github.com/Open-Speech-EkStep/ULCA-asr-dataset-corpus) ⭐ 50 | 🐛 10 | 📅 2022-11-23
* [Microsoft Speech Corpus](https://msropendata.com/datasets/7230b4b1-912d-400e-be58-f84e0512985e)
* [OpenSLR](http://www.openslr.org/resources.php) - {2020, 9 hours, [Paper](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.800.pdf)}
* [IARPA Babel](https://catalog.ldc.upenn.edu/LDC2017S13) - {2017, 350 hours}
* [Mozilla CommonVoice](https://commonvoice.mozilla.org/en/datasets) - {2020, 20 hours}
* [Spoken Tutorial](https://spoken-tutorial.org/) - TODO: Scrape from here

#### Speech Translation

* [CVSS - CommonVoice-based S2S](https://github.com/google-research-datasets/cvss) ⚠️ Archived - {2022, \~3 hours}
* [Prabhupadavani](https://github.com/frozentoad9/CMST) ⭐ 13 | 🐛 1 | 📅 2022-10-12 - {2022, [Paper](https://arxiv.org/pdf/2201.11391.pdf)}

#### Text-to-Speech (TTS)

* [IIT Madras TTS database](https://www.iitm.ac.in/donlab/tts/index.php) - {2020, [Competition](http://tdil-dc.in/ttsapi/ttschallenge2020/)}
* [WikiPron](https://github.com/kylebgorman/wikipron) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-04-07 - Word Pronounciations from Wiki
* [LinguaLibre](https://lingualibre.org/datasets/) - Wiktionary-based word corpus
* [SLR65](http://openslr.org/65) - Crowdsourced high-quality Tamil multi-speaker speech dataset

#### Audio

* [VoxLingua107 - Language Identification dataset](http://bark.phon.ioc.ee/voxlingua107/)
* [Abuse Detection In Multilingual Audio](https://github.com/ShareChatAI/Adima) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2022-05-09 - {2022, [Paper](https://arxiv.org/pdf/2202.07991.pdf)}
* [A classification dataset for Tamil music](http://dorienherremans.com/sgmusic) - {2020, [Paper](https://arxiv.org/abs/2009.04459)}

### Named Entity Recognition

* [Chatbot NER](https://github.com/hellohaptik/chatbot_ner/) ⭐ 334 | 🐛 28 | 🌐 Python | 📅 2026-04-01
* [Tamil Noun Classifier](https://github.com/sarves/Tamil-Noun-Classifier) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2020-11-23
* [University of Moratuwa NER](https://github.com/nlpcuom/Sinhala-and-Tamil-NER) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2019-05-03 - {2019}
* [FIRE2014](http://www.au-kbc.org/nlp/NER-FIRE2014/)
* [FIRE2015 Social Media Text](http://au-kbc.org/nlp/ESM-FIRE2015/) - Tweets
* [WikiAnn](https://elisa-ie.github.io/wikiann) - ([Latest Download Link](https://drive.google.com/drive/folders/1Q-xdT99SeaCghihGa7nRkcXGwRGUIsKN))

### Text Classification

* [AI4Bharat News Article Classification](https://github.com/AI4Bharat/indicnlp_corpus#indicnlp-news-article-classification-dataset) ⭐ 206 | 🐛 10 | 🌐 Python | 📅 2023-04-16

* [A Dataset for Troll Classification of TamilMemes, 2020](https://github.com/bharathichezhiyan/TamilMemes) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-05-16

* [Offensive Language Identification in Dravidian Languages](https://competitions.codalab.org/competitions/27654) - {2020, [Dataset](https://github.com/manikandan-ravikiran/DOSA) ⭐ 0 | 🐛 0 | 📅 2021-02-25}

* [IndicGLUE Classification Benchmark](https://indicnlp.ai4bharat.org/indic-glue/)
  * Headline Classification
  * Wikipedia Section Title Classification
  * Wiki Cloze-style Question Answering

* [iNLTK News Articles Classification](https://www.kaggle.com/disisbig/tamil-news-dataset)

* [TamilMurasu News Articles Classification](https://www.kaggle.com/vijayabhaskar96/tamil-news-classification-dataset-tamilmurasu)

* [Indic Tamil NLP 2018](https://www.kaggle.com/sudalairajkumar/tamil-nlp)
  * Thirukkural Dataset - {Aṟam, Poruḷ, Inbam} classification
  * Movie Review Dataset
  * News Classficaition

### OCR

#### Character-level datasets

* [Tamil Vowels - Scanned Handwritten](https://github.com/anandhkishan/Handwritten-Character-Recognition-using-CNN/tree/master/new_dataset) ⭐ 35 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-22 - {12 vowels, 18 images each}
* [AcchuTamil Printed Characters Dataset](https://github.com/Ezhil-Language-Foundation/acchu-tamilocr-dataset) ⚠️ Archived - {MNIST format}
* [LipiTK Isolated Handwritten Tamil Character Dataset](http://lipitk.sourceforge.net/datasets/tamilchardata.htm) - {156 characters, 500 samples per char}
* [Jaffna University Datasets of printed Tamil characters and documents](http://www.jfn.ac.lk/index.php/data-sets-printed-tamil-characters-printed-documents/)
* [Kalanjiyam: Unconstrained Offline Tamil Handwritten Database](https://kalanjyam.wordpress.com/) - {2016, [Paper](https://link.springer.com/chapter/10.1007/978-3-319-68124-5_24)}

#### Scene-Text Detection / Recognition

* [SynthText](https://ocr.ai4bharat.org/#/previous_works) - {2019}
* [IIIT-H OCR benchmark and synthetic data](https://arxiv.org/abs/2201.03180) - {2021, Available on request}

#### Document OCR

* [Anuvaad OCR Corpus](https://github.com/project-anuvaad/anuvaad-ocr-corpus#tamil) ⭐ 0 | 🐛 0 | 📅 2023-01-27

### Part-Of-Speech (POS) Tagging

* [AUKBC-TamilPOSCorpus2016v1](http://www.au-kbc.org/nlp/corpusrelease.html)
* [ThamizhiPOSt](https://github.com/nlpcuom/ThamizhiPOSt) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2020-11-24
* Treebanks from [Universal Dependencies](https://universaldependencies.org/ta/index.html)

### Sentiment and Abuse Analysis

* [Dravidian-CodeMix: Offensive Language Identification - FIRE2020](https://github.com/bharathichezhiyan/DravidianCodeMix-Dataset) ⭐ 20 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-02-05 - {[Competition](https://dravidian-codemix.github.io/2020/datasets.html), [Paper](https://www.aclweb.org/anthology/2020.sltu-1.28.pdf), [TamilMixSentiment](https://github.com/bharathichezhiyan/TamilMixSentiment) ⭐ 8 | 🐛 0 | 📅 2021-05-16}
  * Implementations: [Theedhum Nandrum](https://github.com/oligoglot/theedhum-nandrum) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2021-04-09
* [Multilingual Abusive Comment Detection - ShareChatAI](https://github.com/ShareChatAI/MACD) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2024-02-22 - 30k samples
* [ACTSEA: Annotated Corpus for Tamil & Sinhala Emotion Analysis](https://github.com/Jenarthanan14/Tamil-Sinhala-Emotion-Analysis) ⭐ 6 | 🐛 1 | 🌐 Java | 📅 2020-01-16
* [Hope Speech Dataset, 2020](https://github.com/bharathichezhiyan/HopeEDI) ⭐ 4 | 🐛 0 | 📅 2021-05-16 ([Competition](https://competitions.codalab.org/competitions/27653))
* [SentiWordNet - SAIL](http://amitavadas.com/SAIL/il_res.html)
* [Twitter Keyword based Emotion Corpus](https://osf.io/48awk/) - {2019}
* [Tamil 1k Tweets For Binary Sentiment Analysis](https://kracekumar.com/post/tamil_1k_tweets_binary_sentiment/)
* [IIIT-D Abusive Comment Identification, 2021](https://www.kaggle.com/c/iiitd-abuse-detection-challenge/data)
* DravidianLangTech 2022
  * [Toxic Span Identification](https://competitions.codalab.org/competitions/36395)
  * [Multimodal Sentiment Analysis](https://competitions.codalab.org/competitions/36406)
  * [Abusive Comment Detection](https://competitions.codalab.org/competitions/36403)
  * [Emotion Analysis](https://competitions.codalab.org/competitions/36396)

### Lexical Resources

* [MTurks Bilngual Dictionary](https://github.com/AI4Bharat/indicnlp_catalog/issues/21) ⭐ 639 | 🐛 150 | 📅 2024-12-14 - {2014}
* [AI4Bharat Word Frequency Lists](https://github.com/AI4Bharat/indicnlp_corpus#text-corpora) ⭐ 206 | 🐛 10 | 🌐 Python | 📅 2023-04-16
* [IIIT-H Word Similarity Database](https://github.com/syedsarfarazakhtar/Word-Similarity-Datasets-for-Indian-Languages) ⭐ 8 | 🐛 0 | 📅 2017-05-23
* [IndoWordNet](http://www.cfilt.iitb.ac.in/indowordnet/)
* [AU-KBC WordNet](http://www.au-kbc.org/nlp/lex_re.html)

### Natural Language Generation

* [XL-Sum: Abstractive Summarization](https://github.com/csebuetnlp/xl-sum) ⭐ 277 | 🐛 0 | 🌐 Python | 📅 2024-03-26
* [XQA: A Cross-lingual Open-domain Question Answering Dataset](https://github.com/thunlp/XQA) ⭐ 89 | 🐛 2 | 🌐 Python | 📅 2021-11-16 - {2019, [Paper](https://www.aclweb.org/anthology/P19-1227.pdf)}
* [XAlign: Cross-lingual Fact-to-Text Alignment and Generation](https://github.com/tushar117/XAlign) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2023-01-01 - {2022, [Paper](https://drive.google.com/file/d/1M9FRYQ-ir9ccfsiXXi1p7EcrELEJGJ_l/preview)}

### Benchmarks

* [XTREME - Multi-task Benchmark for Cross-lingual Generalization](https://github.com/google-research/xtreme) ⚠️ Archived
* [MASSIVE - NLU Benchmark](https://github.com/alexa/massive) ⭐ 564 | 🐛 4 | 🌐 Python | 📅 2022-11-28 - Slot filling, Intent classification, Virtual assistant evaluation
* [Vyākarana - Syntactic evaluation of language models](https://github.com/rajaswa/indic-syntax-evaluation) ⭐ 16 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-02-28 - {2021}
* [XTREME-S: Evaluating Cross-lingual Speech Representations](https://huggingface.co/datasets/google/xtreme_s) - {[Paper](https://arxiv.org/pdf/2203.10752.pdf)}
* [IndicGLUE](https://indicnlp.ai4bharat.org/indic-glue/)

### Miscellaneous NLP Datasets

* **Natural Language Inference**
  * [AI4Bharat Cross-lingual Semantic Textual Similarity](https://github.com/AI4Bharat/indicnlp_catalog/issues/146) ⭐ 639 | 🐛 150 | 📅 2024-12-14 - {2020}
  * [IndicLink - Multilingual Fact Linking](https://github.com/google-research-datasets/IndicLink) ⚠️ Archived - {2022}
  * [XNLI 2019](https://www.gujaratresearchsociety.in/index.php/JGRS/article/view/3426) - Request via email
  * [AI4Bharat Cross-Lingual Sentence Retrieval](https://indicnlp.ai4bharat.org/indic-glue/)
  * [Multilingual Entity-Linking from WikiNews](http://goo.gle/mewsli-dataset) - {2020}

* **Dialogue**
  * [Code-Mixed-Dialog 2018](https://github.com/sumanbanerjee1/Code-Mixed-Dialog) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2018-06-20

* **Information Extraction**\
  (*Can also be event extraction or entity extraction*)

  * [EventXtractionIL-FIRE2018](http://78.46.86.133/EventXtractionIL-FIRE2018/)
  * [EDNIL-FIRE2020](https://ednilfire.github.io/ednil/2020/index.html)
  * [CMEE-FIRE2016](http://www.au-kbc.org/nlp/CMEE-FIRE2016/)

* **Misc**
  * [WIT : Wikipedia-based Image Text Dataset, 2021](https://github.com/google-research-datasets/wit) ⚠️ Archived
  * [AllNewLyrics Dataset - Tamil Song Lyrics](https://github.com/praveenraj0904/tamillyricscorpus) ⭐ 1 | 🐛 0 | 📅 2021-02-28 - {2021, [Paper](https://www.aclweb.org/anthology/2021.dravidianlangtech-1.1/)}
  * [MMDravi - Image Captioning and Translation Benchmark, 2019](https://github.com/bharathichezhiyan/multimodalmachinetranslation-Tamil) ⭐ 0 | 🐛 0 | 📅 2021-05-16 - Contains manually annotated data for dev & tests from Flickr30k dataset
  * [Paraphrase Identification - Amrita University-DPIL Corpus](https://nlp.amrita.edu/dpil_cen/index.html)
  * [Anaphora Resolution from Social Media Text - FIRE2020](http://78.46.86.133/SocAnaRes-IL20/)
  * [TamilPaa Song-Lyrics Dataset, 2020](https://www.kaggle.com/sivaskvs/tamil-songs-lyrics-dataset)

* **Reasoning**
  * [Cross-lingual Choice of Plausible Alternatives](https://github.com/cambridgeltl/xcopa) ⭐ 105 | 🐛 1 | 📅 2021-02-04 (XCOPA)

* MorphAnalysis
  * [AI4Bharat MorphAnalyzer](https://github.com/ai4bharat/indicnlp_corpus#morphanalyzers) ⭐ 206 | 🐛 10 | 🌐 Python | 📅 2023-04-16
  * [ThamizhiMorph](https://github.com/sarves/thamizhi-morph) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2026-05-06

* **Pure Tamil**
  * [Indic to Pure Tamil](https://github.com/narVidhai/Indic-To-Pure-Tamil) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2020-12-22
  * [Thamizhi Word Validator](https://github.com/sarves/thamizhi-validator) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2021-06-11
  * [English to Tamil](https://www.kaggle.com/muthua/tamil-loan-words-classification)
  * [Tamil Glossary Dataset](https://osf.io/ngt6v/)

***

## **Other Important Resources**

* [IndicNLP Catalog](https://github.com/AI4Bharat/indicnlp_catalog) ⭐ 639 | 🐛 150 | 📅 2024-12-14 by AI4Bharat
* [The Big Bad NLP Database](https://datasets.quantumstat.com/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
