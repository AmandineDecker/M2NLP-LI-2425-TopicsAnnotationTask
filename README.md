# M2NLP-LI-2425-TopicsAnnotationTask
Repository for the Dialogue, ChatBot and QA course (M2 TAL, LI)

## Project

### Annotations

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

### Cross-validation

Correct the annotations for the sub-segments you were allocated on Arche.
Use the following tool: https://amandinedecker.github.io/SDRTAnno/SDRT-anno/

Process:
- Download the .json files corresponding to your spans of utterances;
- Upload the first one in the web tool;
- Correct the annotations by deleting the edges you disagree with (click on the edge, then click on <<span style="font-variant:small-caps;">remove edge</span>>) and adding new ones;
- Repeat the process with the other files.

Remarks:
- The .json files may cover more than the span you are supposed to correct, you do not need to correct everything but use the context to annotate properly;
- You have access to a graph representation and a summary of the relations in the folder `visualisation', you can use them to navigate the existing annotations more easily;
- Note that the graph may have issues when some utterances are too long, when the utterances do not follow the pattern ``Spk-Digit: txt'' or when the annotation process was not respected.

When you are done, download your corrected annotations and upload them on Arche. You can upload a .txt file with additional comments if needed.

## Corpus

The transcripts and recordings are from the Saarbrücken Corpus of Spoken English (SCoSE) available from Talkbank.

The corpora available from [TalkBank](https://talkbank.org/), and the adapted format within this repository,
are licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>