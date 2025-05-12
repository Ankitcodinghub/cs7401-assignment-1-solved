# cs7401-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS7401 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs7401-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91713&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS7401 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

General Instructions

<ol>
<li>The assignment must be implemented in Python</li>
<li>No standard library for calculating n-grams, tokenization or LMs should be used.</li>
<li>Submitted assignment must be your original work. Please do not copy any part from any source including your friends, seniors, and/or the internet. If any such attempt is caught then serious actions including an F grade in the course is possible.</li>
<li>A single .zip file needs to be uploaded to the Moodle Course Portal.</li>
<li>Your grade will depend on the correctness of answers and output. In addition, due consideration will be given to the clarity and details of your answers and the legibility and structure of your code.</li>
<li>Please start early, since no extension to the announced deadline would be possible.</li>
</ol>
1 Tokenization

You have been given a twitter corpus for cleaning. Your task is to design a tokenizer using regex, which you will later use for smoothing as well.

1. Create a Tokenizer to handle following cases:

(a) Word Tokenizer (b) Punctuation

(c) URLs

(d) Hashtags (#manchesterisred)

(e) Mentions (@john)

2. For the following cases, replace the tokens with appropriate placeholders:

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) URLs: &lt;URL&gt;

(b) Hashtags: &lt;HASHTAG&gt;

(c) Mentions: &lt;MENTION&gt;

Original

#ieroween THE STORY OF IEROWEEN! THE VIDEO -»»»»»»»»»»» http://bit.ly/2VFPAV «« JUST FOR FRANK !!! ÃƒÂ§

</div>
<div class="column">
Cleaned

&lt;HASHTAG&gt; THE STORY OF IEROWEEN! THE VIDEO -&gt; &lt;URL&gt; &lt; JUST FOR FRANK ! ÃƒÂ§

</div>
</div>
<div class="layoutArea">
<div class="column">
Example output after placeholder substitution

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Apart from these, you are also encouraged to try other tokenization and placeholder substitution schemes based on your observations from the corpora used for the smoothing task to achieve a better language model. You’ll find percentages, age values, expressions indicating time, time periods occurring in the data. You’re free to explore and add multiple such reasonable tokenization schemes in addition from the ones listed above. Specify any such schemes you use in the final README.

2 Smoothing

You have been given two corpus : EuroParl corpus, and Medical Abstracts corpus. Your task is to design Language Models for both of these corpora using smoothing. Ensure that you use the tokenizer created in task 1 for this task.

</div>
</div>
<div class="layoutArea">
<div class="column">
1.

2.

3.

3

</div>
<div class="column">
Create language models with the following parameters:

(a) On EuroParl corpus:

i. LM 1: tokenization + 4-gram LM + Kneyser-Ney smoothing

ii. LM 2: tokenization + 4-gram LM + Witten-Bell smoothing (b) On Medical Abstracts corpus:

i. LM 3: tokenization + 4-gram LM + Kneyser-Ney smoothing ii. LM 4: tokenization + 4-gram LM + Witten-Bell smoothing

For each of these corpora, create a test set by randomly selecting 1000 sentences. This set will not be used for training the LM.

<ol>
<li>(a) &nbsp;Calculate perplexity score for each sentence of EuroParl corpus and Medical Abstracts corpus for each of the above models and also get average perplexity score/corpus/LM on the train corpus</li>
<li>(b) &nbsp;Report the perplexity scores for all the sentences in the test set. Report the perplexity score on the test sentences as well, in the same manner above.</li>
</ol>
Compare and analyse the behaviour of the different LMs and put your analysis and visualisation in a report

Corpus

</div>
</div>
<div class="layoutArea">
<div class="column">
The following corpora have been given to you for training:

<ol>
<li>Tweets corpus (A set of 2000 tweets)</li>
<li>Europarl Corpus (A subset of 20000 lines from English side of the dataset for English-French trans- lation)</li>
<li>Medical Abstracts Corpus (A subset of 20000 sentences from English side of the English-German translation task for medical abstracts in WMT 2014)</li>
</ol>
The first one is to be used for figuring out rules for the tokenization task. Use 2 &amp; 3 for training your LMs. Please download the corpus files from this link.

4 Submission Format

Zip the following into one file and submit in the Moodle course portal. Filename should be &lt;roll num- ber&gt;_&lt;assignment1&gt;.zip, eg: 2021xxxxxx_assignment1.zip:

1. Source Code:

(a) language_model.py: Runs the language model given the following:

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<pre>$ python3 language_model.py &lt;n_value&gt; &lt;smoothing type&gt; &lt;path to corpus&gt;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Smoothing type can be k for Kneyser-Ney or w for Witten-Bell. On running the file, the expected output is a prompt, which asks for a sentence and provides the probability of that sentence using the two smoothing mechanisms. Therefore, an example would be:

<pre>                     $ python3 language_model.py k ./corpus.txt
                     input sentence: I am a man.
                     0.89972021
</pre>
<ol start="2">
<li>A text file containing cleaned output (with placeholders) for all the tweets stored in &lt;roll num- ber&gt;_tokenize.txt</li>
<li>Report containing the perplexity scores of all LMs and your analysis of the results in a PDF:

(a) For each LM, submit a text file with perplexity scores of each sentences in the following format:

<pre>                     avg_perplexity
                     sentence_1 &lt;tab&gt; perplexity
                     sentence_2 &lt;tab&gt; perplexity
                     ..
</pre>
(b) Namingmustbe:&lt;rollnumber&gt;_LM1_train-perplexity.txt,&lt;rollnumber&gt;_LM1_test-perplexity.txt
</li>
<li>README on how to execute the files, how to get perplexity of sentences along with any other infor- mation.</li>
</ol>
6 Resources

1. Chapter 3 of the Speech and Language Processing book by Jurafsky &amp; Martin

2. An Empirical Study of Smoothing Techniques for Language Modeling for Witten-Bell Smoothing 3. Official Python documentation and testing playground for regex.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
