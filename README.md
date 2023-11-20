# Manual knowledge annotations of German plays in Q:TRACK

In this repository we provide the annotations created 
in the digital humanities project [Q:TRACK](https://quadrama.github.io/). 
The annotations target processes of knowledge distribution among characters in German plays. 
For more details, see [the annotation guideline](https://zenodo.org/record/5729707) (in German). 
You can find the following data in this repository:

- round 1: Annotations in round 1 were part of the process of guideline development. 
- round 2: The guidelines were largely consolidated and inter-annotator agreement could be calculated. Texts of round 2 are provided in their initial version that was used for IAA calculation.
- round 3: In round 3, every play was checked by at least one annotator based on a discussion of issues. Also, annotations for the categories ``murderer\_of(A, B)``, ``dead(A)`` and ``unborn\_child\_of(A, B)`` were added.

All annotations are provided in their original annotation format used by the 
[CorefAnnotator](https://github.com/nilsreiter/CorefAnnotator/) and as a csv-export. Columns in the csv files are:

- begin: Character position of the beginning of the annotation span (character as in 'written symbol')
- end: Character position of the end of the annotation span
- leftContext: The left context of the annotation span
- surface: The annotation span
- rightContext: The right context of the annotation span
- entityNum: Index of the annotation label
- entityLabel: The annotation label
- entityGroup: (not used in this annotation project)

The original TEI-XML files used for the annotation can be found in the data of the [German Drama Corpus (GerDraCor)](https://dracor.org/ger).
These can be used to resolve the character position of the annotations (columns "begin" and "end").

The following table gives an overview of the annotated plays. 
Numbers in the columns round-1 to round-3 indicate the number of annotations available for this version.

| id | author                              | text                                | round-1 | round-2 | round-3 |
|----|-------------------------------------|-------------------------------------|---------|---------|---------|
| 1  | Lessing, Gotthold Ephraim           | Nathan der Weise                    | 2       |         | 2       |
| 2  | Lessing, Gotthold Ephraim           | Emilia Galotti                      | 2       |         | 2       |
| 3  | Goethe, Johann Wolfgang             | Die natürliche Tochter              | 2       |         | 2       |
| 4  | Goethe, Johann Wolfgang             | Iphigenie auf Tauris                | 2       |         | 2       |
| 5  | Klinger, Friedrich Maximilian       | Die Zwillinge                       | 2       |         | 2       |
| 6  | Hofmannsthal, Hugo von              | Der Rosenkavalier                   | 2       |         | 1       |
| 7  | Goethe, Johann Wolfgang             | Stella                              | 2       |         | 2       |
| 8  | Kleist, Heinrich von                | Die Familie Schroffenstein          | 2       |         | 2       |
| 9  | Hofmannsthal, Hugo von              | Elektra                             | 2       |         | 1       |
| 10 | Hebbel, Friedrich                   | Maria Magdalene                     | 2       |         | 1       |
| 11 | Lenz, Jakob Michael Reinhold        | Der Hofmeister                      | 2       |         | 1       |
| 12 | Schiller, Friedrich                 | Die Braut von Messina               | 2       |         | 1       |
| 13 | Pfeil, Johann Gottlob Benjamin      | Lucie Woodvil                       | 2       |         | 1       |
| 14 | Grillparzer, Franz                  | Die Ahnfrau                         | 2       |         | 1       |
| 15 | Schnitzler, Arthur                  | Komtesse Mizzi oder Der Familientag | 2       |         | 1       |
| 16 | Schiller, Friedrich                 | Die Räuber                          | 2       |         | 1       |
| 17 | Günderrode, Karoline von            | Magie und Schicksal                 |         | 2       | 1       |
| 18 | Günderrode, Karoline von            | Udohla                              |         | 2       | 1       |
| 19 | Weißenthurn, Johanna von            | Das Manuscript                      |         | 2       | 1       |
| 20 | Gottsched, Luise Adelgunde Victorie | Das Testament                       |         | 2       | 1       |
| 21 | Goethe, Johann Wolfgang             | Clavigo                             |         | 2       | 1       |
| 22 | Hauptmann, Gerhart                  | Vor Sonnenaufgang                   |         | 2       | 1       |
| 23 | Schlegel, Johann Elias              | Canut                               |         | 2       | 1       |
| 24 | Brentano, Clemens                   | Ponce de Leon                       |         | 2       | 1       |
| 25 | Eichendorff, Joseph von             | Die Freier                          |         | 2       | 1       |
| 26 | Wagner, Heinrich Leopold            | Die Kindermörderin                  |         | 2       | 1       |
| 27 | Wagner, Richard                     | Die Walküre                         |         | 2       | 1       |
| 28 | Schiller, Friedrich                 | Maria Stuart                        |         | 2       | 1       |
| 29 | Lessing, Gotthold Ephraim           | Miß Sara Sampson                    |         | 2       | 1       |
| 30 | Gellert, Christian Fürchtegott      | Die zärtlichen Schwestern           |         | 2       | 1       |

## Publications

Melanie Andresen, Benjamin Krautter, Janis Pagel, Nils Reiter. Who Knows What in German Drama? A Composite Annotation Scheme for Knowledge Transfer. Annotation, Evaluation, and Analysis. Journal of Computational Literary Studies, 1, 2022. [http://dx.doi.org/10.48694/jcls.107](http://dx.doi.org/10.48694/jcls.107).

Melanie Andresen, Benjamin Krautter, Janis Pagel, Nils Reiter. Nathan nicht ihr Vater? – Wissensvermittlungen im Drama annotieren. In DHd 2022 Kulturen des digitalen Gedächtnisses. 8. Tagung des Verbands "Digital Humanities im deutschsprachigen Raum" (DHd 2022), Potsdam, Germany, March 2022. [http://dx.doi.org/10.5281/zenodo.6327913](http://dx.doi.org/10.5281/zenodo.6327913).

## Contact

see [Q:TRACK website](https://quadrama.github.io/people.de)