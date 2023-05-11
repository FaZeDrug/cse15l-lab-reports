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

Using the option `grep -v [pattern] [file] ` will print the lines that do not match the file.

This is the command I have used to grep inside the Media folder, which is inside the government folder.

```
$ grep -v "legal" stringsearch-data/technical/government/Media/5_Legal_Groups.txt
```

This is the output:

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








