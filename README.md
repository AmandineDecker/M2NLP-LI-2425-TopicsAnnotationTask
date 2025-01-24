# M2NLP-LI-2425-TopicsAnnotationTask
Repository for the Dialogue, ChatBot and QA course (M2 TAL, LI)

## Project

Segment your piece of conversation in topics and annotate with topical structure.
Use the following tool: https://amandinedecker.github.io/SDRTAnno/SDRT-anno/

Annotation process:
- Use the *joint* relation to build topics: select two subsequent utterances that you consider belong to the same topic and use the button <<span style="font-variant:small-caps;">join nodes</span>>;
- Use the labels and <<span style="font-variant:small-caps;">add edge</span>> button to annotate the topics: select the last utterance of your first topic and the first utterance of your last topic, select the label, and use the button <<span style="font-variant:small-caps;">add edge</span>>.

Remarks:
- Do __not__ use the Safari browser;
- You can use the button <<span style="font-variant:small-caps;">join all nodes</span>> to add the *joint* relation between all subsequent nodes, you can then remove the edges between topics;
- We wrote a few guidelines for the annotations here: https://bul.univ-lorraine.fr/index.php/s/btr56kB3bsXkrAz.

When you are done, download your annotation (red button on the right) and upload it on Arche. Put your name and segment number in your file name (*eg.* bob_seg3.json).

## Corpus

The transcripts and recordings are from the Saarbrücken Corpus of Spoken English (SCoSE) available from Talkbank.

The corpora available from [TalkBank](https://talkbank.org/), and the adapted format within this repository,
are licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>