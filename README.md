# StatisticalLanguageModeling

This program shows the usage of some simple statistical models of English text. The data files contain 
unigram and bigram counts for 500 frequently occurring tokens in English text. These tokens include 
actual words as well as punctuation symbols and other textual markers. In addition, an “unknown” token
is used to represent all words that occur outside this basic vocabulary.

### unigram distribution

For example, if we want to compute the maximum likelihood estimate of the unigram distribution Pu(w)
over words w, where w are words that start with a 'M', by running the program we have:

MILLION            unigram probability: 0.002073

MORE               unigram probability: 0.001709

MR.                unigram probability: 0.001442

MOST               unigram probability: 0.000788

MARKET             unigram probability: 0.000780

MAY                unigram probability: 0.000730

M.                 unigram probability: 0.000703

MANY               unigram probability: 0.000697

MADE               unigram probability: 0.000560

MUCH               unigram probability: 0.000515

MAKE               unigram probability: 0.000514

MONTH              unigram probability: 0.000445

MONEY              unigram probability: 0.000437

MONTHS             unigram probability: 0.000406

MY                 unigram probability: 0.000400

MONDAY             unigram probability: 0.000382

MAJOR              unigram probability: 0.000371

MILITARY           unigram probability: 0.000352

MEMBERS            unigram probability: 0.000336

MIGHT              unigram probability: 0.000274

MEETING            unigram probability: 0.000266

MUST               unigram probability: 0.000267

ME                 unigram probability: 0.000264

MARCH              unigram probability: 0.000260

MAN                unigram probability: 0.000253

MS.                unigram probability: 0.000239

MINISTER           unigram probability: 0.000240

MAKING             unigram probability: 0.000212

MOVE               unigram probability: 0.000210

MILES              unigram probability: 0.000206

etc.

### bigram distribution
Running the program, we can also obtain the maximum likelihood of the bigram distribution.

For example, the ten most likely words w' to follow the word “ONE” are (along with their bigram probabilities):

HUNDRED            bigram probability:   0.209061

<UNK>              bigram probability:   0.124304

.POINT             bigram probability:   0.099952

OF                 bigram probability:   0.073947

THOUSAND           bigram probability:   0.068654

MILLION            bigram probability:   0.031832

,COMMA             bigram probability:   0.031622

-HYPHEN            bigram probability:   0.030479

HALF               bigram probability:   0.029139

.PERIOD            bigram probability:   0.024376

