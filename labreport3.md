# Lab Report 3 - Week 6

Hello! Here is my Lab Report 3 - Research and Commands


**Chosen Command**

The command I have chosen is `grep `.

The `grep` command is a command-line tool that searches for a given string in a file (or multiple files) and prints all the lines that match that string.



**How does `grep` work?**

To use the `grep` command, this is the format:

`grep [options] [pattern] [file]`

*  `grep`: This is the command itself
* `options`: Grep has options that can modify its behavior. It is not necessary to include an option for grep, but I will be exploring them further in this lab report.
* `pattern`: The pattern is the text string you want to search for.
* `file`: This is the file (or files) you want to use grep on.

**Interesting Ways to Use `grep`**

# 1) `-v` to print the lines that do not match the pattern

Using the option `grep -v [pattern] [file] ` will print the lines that do not match the given pattern in that file. This command is useful because you can narrow down your search by filtering out lines that match the pattern, and return the lines that do not have that line. It is almost like an inverted search tool!

I found the -v option of `grep` through ChatGPT.

This is the command I have used to grep inside the Media folder, which is inside the government folder.

```
$ grep -v "legal" stringsearch-data/technical/government/Media/5_Legal_Groups.txt
```

This is the output: (note that the string 'Legal' is still included, as I was searching for the lowercase version of the word)

```
BY EDWARD MCDONOUGH
services to the poor, ethnic minorities, seniors and people with
disabilities have joined together to acquire a west-side downtown
building where they will have their offices. The new Community
Legal Center at 205 N. 400 West is a project of "And Justice for
All," which, until this venture, has been a joint fund-raising
services. "And Justice for All," which solicits donations primarily
from Utah lawyers and foundations, was the first joint fund-raising
Community Legal Center is the first joint office project of public
service law groups.
The Legal Aid Society of Salt Lake, the Disability Law Center,
the Multi-Cultural Legal Center, the Senior Lawyer Volunteer
Project and Utah Legal Services will share the new facility, and
last Wednesday their board members were given a tour of the
Community Legal Center hosted by staff members of the five
agencies. All of the agencies can share the same reception area and
client waiting room. The building is close in, across the street
from West High and two blocks from the Gateway. It has its own
parking, something that's hard to find downtown and which has been
a problem for staff as well as clients. Owning and sharing the
building and not paying rent times five will save the non-profit
agencies about $375,000 each year. My assistant, Charity
Christenson, pointed out that the shared facility will also be
desperate for a protective order, for example, have to run all over
town trying to find the right agency.
After the tour, we found Jaye Olafson at the cookies and
brownies reception on the first floor. Jaye and her husband, Erik,
own Tomax Technologies and were the sellers of the building. Jaye
explained how much of the renovation had been merely uncovering
what was already there. The hardwood floors, wooden ceilings and
brick and stone interior walls were all hidden behind coverings and
old paint. She loves the building, and they only moved out because
the business had outgrown the space. So they renovated the old
Sweet Candy Company building for Tomax. The Olafsons are delighted
with the new owners. The building had been like home, she
explained, and so it was important who would be living there. I
noted on the donor list that the couple, through Olafson Group, had
become one of the major supporters of the project.
Stewart Ralphs, the executive director of the Legal Aid Society,
explained that the Community Legal Center Campaign still has a long
ways to go, with a bit more than half of the $4 million projected
cost received so far. There still needed to be furnishings and
office equipment and such. He promised that they would be getting
in touch with us later on the subject.
```

This use of -v with grep searches for lines in the file ` stringsearch-data/technical/government/Media/5_Legal_Groups.txt` and prints the linesthat do not contain the string "legal". This is useful if I wanted to see the lines that exclude "legal", since that is mentioned a lot in the file.


Another command I have used is this:

```
$ grep -v "we" stringsearch-data/technical/911report/preface.txt
```

This is the output of that command: (note that the string 'We' is still included, as I was searching for the lowercase version of the word)

```
PREFACE
            We present the narrative of this report and the recommendations that flow from it to
                the President of the United States, the United States Congress, and the American
                people for their consideration. Ten Commissioners-five Republicans and five
                Democrats chosen by elected leaders from our nation's capital at a time of great
                partisan division-have come together to present this report without dissent.
            We have come together with a unity of purpose because our nation demands it.
                September 11, 2001, was a day of unprecedented shock and suffering in the history of
                avoid such tragedy again?
                Commission on Terrorist Attacks Upon the United States (Public Law 107-306, November
                27, 2002).
                relating to the terrorist attacks of September 11, 2001," including those relating
                to intelligence agencies, law enforcement agencies, diplomacy, immigration issues
                and border control, the flow of assets to terrorist organizations, commercial
                aviation, the role of congressional oversight and resource allocation, and other
                individuals in ten countries. This included nearly every senior official from the
                current and previous administrations who had responsibility for topics covered in
                our mandate. We have sought to be independent, impartial, thorough, and nonpartisan.
                public testimony from 160 witnesses.
            Our aim has not been to assign individual blame. Our aim has been to provide the
                fullest possible account of the events surrounding 9/11 and to identify lessons
                learned.
            We learned about an enemy who is sophisticated, patient, disciplined, and lethal. The
                enemy rallies broad support in the Arab and Muslim world by demanding redress of
                political grievances, but its hostility toward us and our values is limitless. Its
                purpose is to rid the world of religious and political pluralism, the plebiscite,
                targets. Collateral damage is not in its lexicon.
            We learned that the institutions charged with protecting our borders, civil aviation,
                and national security did not understand how grave this threat could be, and did not
                adjust their policies, plans, and practices to deter or defeat it. We learned of
                sharing information across a large and unwieldy government that had been built in a
                different era to confront different dangers.
                We hope that the terrible losses chronicled in this report can create something
                together as a nation. The test before us is to sustain that unity of purpose and
                meet the challenges now confronting us. We need to design a balanced strategy for
                the same time protecting our country against future attacks. We have been forced to
                think about the way our government is organized. The massive departments and
                accountability.
                Commissioners, whose dedication to this task has been profound. We have reasoned
                together over every page, and the report has benefited from this remarkable
                dialogue. We want to express our considerable respect for the intellect and judgment
            We want to thank the Commission staff. The dedicated professional staff, headed by
                Philip Zelikow, has contributed innumerable hours to the completion of this report,
                setting aside other important endeavors to take on this all-consuming assignment.
                They have conducted the exacting investigative work upon which the Commission has
                built. They have given good advice, and faithfully carried out our guidance. They
                have been superb. We thank the Congress and the President. Executive branch agencies
                have searched records and produced a multitude of documents for us. We thank
                insight. The PENTTBOM team at the FBI, the Director's Review Group at the CIA, and
                Inspectors General at the Department of Justice and the CIA provided great
                to detail, and readiness to share what they have learned. We have built on the work
                fine work helped us get started. We thank the City of New York for assistance with
                documents and witnesses, and the Government Printing Office and W.W. Norton
                & Company for helping to get this report to the broad public.
            We conclude this list of thanks by coming full circle: We thank the families of 9/11,
                whose persistence and dedication helped create the Commission. They have been with
                us each step of the way, as partners and witnesses. They know better than any of us
                every knowledgeable person or found every relevant piece of paper. New information
                inevitably will come to light. We present this report as a foundation for a better
                understanding of a landmark in the history of our nation.
            We have listened to scores of overwhelming personal tragedies and astounding acts of
                heroism and bravery. We have examined the staggering impact of the events of 9/11 on
                the American people and their amazing resilience and courage as they fought back. We
                have admired their determination to do their best to prevent another tragedy while
                preparing to respond if it becomes necessary. We emerge from this investigation with
                enormous sympathy for the victims and their loved ones, and with enhanced respect
                for the American people. We recognize the formidable challenges that lie ahead.
            We also approach the task of recommendations with humility. We have made a limited
                most important, whose implementation can make the greatest difference. We came into
                this process with strong opinions about what would work. All of us have had to
                considered the views of others. We hope our report will encourage our fellow
                citizens to study, reflect-and act.
            Thomas H. Kean, chair
            Lee H. Hamilton, vice chair
```

This use of -v with grep searches for lines in the file `stringsearch-data/technical/911report/preface.txt` and prints the lines that do not contain the string "we". This is useful if I wanted to see the lines that exclude "we", since that is mentioned a lot in the file.


# 2) `-i` to perform a case-insensitive search

Using the option `grep -i [pattern] [file] ` will disregard the case-sensitivity of the word you are searching for and print the lines that match it. By default, grep is case-sensitive, so this option is useful if you want to disregard the case-sensitivity of the word you are searching for in files.

I found the -i option of `grep` through ChatGPT.

This is the command I have used:


```
$ grep -i "evolution" stringsearch-data/technical/plos/journal.pbio.0020071.txt
```

This is the output:

```
Evolution is a complex phenomenon that requires a broad understanding of many areas of
        classic text on evolution (1998) contains 26 chapters totaling 763 pages. To cover the
        Evolution: A Very Short Introduction , is no mean feat.
        points. By contrast, most evolutionary textbooks (other than those purely on human
        evolution) tend to focus on nonhuman organisms. As with traits in every other organism,
        relevance of evolution. For example, to explain how mutation can cause the loss of a
        provide only a brief mention of one important process—development. Evolutionary
        insights into our understanding of the mechanisms of evolution. For example, the absence of
        constraints can actually alter the direction of evolution. Although the key forces driving
        evolution are usually thought of as mutation, genetic drift, natural selection, and
        developmental constraints, can also determine the rate and direction of evolution.
        understand from an evolutionary point of view. These ‘difficult problems’ are ageing,
        either been explained or will eventually be explained by modern evolutionary theories, and
        unknown mechanisms might be essential for the evolution of the complex traits. I realize
        that opponents of modern evolutionary theory, such as creationists, have often cited these
        traditional problems to support their conclusion that modern evolutionary theory is wrong;
        mechanisms still to be discovered that play a key role in evolution. Describing potentially
        evolutionary biology with the hope that there are still some theoretical battles to be
        Charlesworths' book, providing evidence for evolution occupies 49 of the 130 pages. They
        evolution (Chapter 3) and subsequently discuss evidence from the geographical distributions
        about a teaching controversy concerning evolution (Scott and Branch 2003), I began to
        convincing readers of the reality and cogency of evolution and evolution theory by astutely
        In Japan, there seem to be few people who deny the facts of evolution, although there
        convince creationists of evolution is usually extremely difficult, if not impossible,
        recommend it to anyone who wants to know about evolution. Moreover, I can recommend it to
        Japanese students not only as an introduction to evolution, but also as an exercise in
```

This use of -i with grep searches for and prints the lines in the file stringsearch-data/technical/plos/journal.pbio.0020071.txt that contain any case-insensitive version of evolution, such as "Evolution" or "evolution".This is useful if I wanted to search for any case-insensitive version of "evolution"

Another command I have used is this:

```
$ grep -i "cells" stringsearch-data/technical/plos/journal.pbio.0020071.txt
```

This is the output of that command:

```
altruism, human consciousness, complex adaptations, and the origin of living cells.
        basic background of biology, such as the gene, DNA, and cells. When I read a recent article
```

This use of -i with grep searches for and prints the lines in the file stringsearch-data/technical/plos/journal.pbio.0020071.txt that contain any case-insensitive version of cells, such as "Cells" or "cells". This is useful if I wanted to search for any case-insensitive version of "cells".


# 3) `n` to perform a case-insensitive search

Using the option `grep -n [pattern] [file] ` prints the line numbers of the word you are searching for, as well as those lines. This option is useful because you can see the line numbers of the word you want to search for, so that you can see exactly what line the word appears on in the file.

I found the -n option of `grep` through ChatGPT.

This is the command I have used:


```
$ grep -n "medicine" stringsearch-data/technical/plos/journal.pbio.0020063.txt
```

This is the output:

```
23:        be—scientifically, ethically, and socially responsible medicine, which means research that
90:        PLoS Medicine community at http://www.plos.org/medicine and help us to
```

This use of -n with grep searches for lines in the file stringsearch-data/technical/plos/journal.pbio.0020063.txt that contain "medicine" and prints the line numbers it appears on, as well as those lines. This is useful if I was doing research on medicine and wanted to see the lines that "medicine" was located on.

Another command I have used is this:

```
$ grep -n "tumors" stringsearch-data/technical/plos/journal.pbio.0020063.txt
```

This is the output:

```
62:        10.1371/journal.pbio.0020007) on the microarray analysis of tumors and one by Sarah
```

This use of -n with grep searches for lines in the file stringsearch-data/technical/plos/journal.pbio.0020063.txt that contain "tumors" and prints the line numbers it appears on, as well as those lines. This is useful if I was doing research on tumors and wanted to see the lines that "tumors" was located on, and see if it was a useful source to use depending on the amount of lines that contain "tumors".

# 4) `w` to perform an exact word search

Using the option `grep -w [pattern] [file] ` searches for and prints the lines of that exact word, and not as a substring. This option is useful because you can use it if you want to search for the exact word. 

I found the -w option of `grep` through ChatGPT.

This is the command I have used:

```
$ grep -w "cytoskeleton" technical/plos/journal.pbio.0020100.txt
```

This is the output:
```
expression and regulation of the actin cytoskeleton and of actin binding proteins in a real
        The cytoskeleton is a meshwork of protein polymers extending throughout the cytoplasm.
        particularly clear example of this is the use of actin cytoskeleton as a “wool” for
        organisation of the actin cytoskeleton.
        cytoskeleton to others affecting cell cycle progression, cytokinesis, and cell shape. They
        coordinate and regulate the activity of the cytoskeleton in the generation of shape and
```

This use of -w with grep searches for lines in the file stringsearch-data/technical/plos/journal.pbio.0020063.txt that searches for the whole word "cytoskeleton" and prints those lines. This is useful if I wanted to only see the lines that contain the exact word "cytoskeleton", and not any other version like "cytoskeletonal".


Another command I have used is this:

```
$ grep -w "protein" technical/plos/journal.pbio.0020100.txt
```

This is the output:
```
The cytoskeleton is a meshwork of protein polymers extending throughout the cytoplasm.
        Clones of cells lacking CAP (Figure 1), a protein known to inhibit actin polymerisation,
        family proteins that catalyse filament formation, and Abl, a protein kinase that binds CAP
        experiments, since the same protein can have different effects depending on the cell type.
```

This use of -w with grep searches for lines in the file stringsearch-data/technical/plos/journal.pbio.0020063.txt that searches for the whole word "protein" and prints those lines. This is useful if I wanted to only see the lines that contain the exact word "protein", and not any other version like "proteins" or "lipoprotein".












