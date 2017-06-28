The Tagging Features in the Notes
=================================

The UBN is composed in markdown language, which uses tags beginning with the hashtag (#), also called  the pound sign. In addition to the current inventory of tags for the UBN project, anyone is free to propose more tags. Any manager-reviser will have the authority to accept or reject such requests.

Remark: these tags are sorted into four groups, as presented below. Because it is important for writers and manager-revisers to remember the order of these four groups, we propose the follow mnemonic phrase: "Failure to Sleep Reduces Well-being" -- Filtering, Scripture, Resource, Working. If you do not like this phrase, maybe you will find this one better: “Forgiven Sinners Rise to Worship.”  

Remark: Each tag must go on its own line after a note, with only a few exceptions as noted below

Filtering Tags
---------------

These tags will allow users to find certain kinds of notes. 

**ALL FILTERING TAGS SHOULD BE PLACED AS THE FIRST GROUP OF TAGS AFTER EVERY NOTE.**

- Verse number (#vn). (Examples: #v1, #v2-4) Put this tag immediately after every note. Any note lacking this tag will not appear in the database of notes.
- Advanced level note (#adv). This tag marks advanced level notes; basic level notes go untagged for level. See the explanation of advanced level notes in section 4.1 above.
- Biblical theme (#bt-xxx). (Example: #bt-judgment) This tag allows users to locate notes having to do with distinct biblical themes, such as redemption, judgment, heaven, sin, etc. For example, if a writer composes a note on Mark 1:11 ("A voice called from heaven, 'You are my beloved Son; with you I am very pleased'"), he may wish to mark it with the #bt-christ tag. As a result, this note will appear if a user searches for notes relevant to the biblical theme of Christology.
- Theological stance (#ts-xxx). (Example: #ts-infantbap) This tag is used to mark notes that give theological positions that fall outside of WA's Core beliefs. 

These tags are available to attach to notes that present a viewpoint that is not shared by all Christians. Notes favoring theological positions that are not included in WA’s Core beliefs should be tagged in this way so that these notes can be kept from publication for now. They will be reserved for possible publication in the future, in an expanded version of the notes. See https://www.wycliffeassociates.org/who-we-are/our-core-beliefs to find WA’s core beliefs stated. 

Sometimes we may write a note that unconsciously favors a certain theological stance. If a  manager-reviser determines that a note favors a certain theological stance, steps must be taken either to make the note more balanced, or to add the theological stance tag.

On the other hand, if a note presents both sides of a controversy in an even-handed manner (as judged by the manager-reviser), then no theological stance tag should be required.


Scripture-Linking Tags
----------------------

These tags allow writers to link notes to other Scripture passages. 

**THESE TAGS SHOULD BE PLACED AFTER ALL SUITABLE FILTERING TAGS HAVE BEEN PLACED.**

- Allusion (#xa-xxx). (Example: #xa-isa40:3) To say that a biblical writer is alluding to another passage is to claim that, in your judgment, the writer is consciously drawing the reader’s attention to that passage without actually quoting it.
- Direct quote (#xq-xxx). (Example: #xq-gen12:3) Remember that biblical writers may quote passages either strictly or loosely. They may combine two or more distinct passages into what appears as one quotation. They may also quote from either the Hebrew Bible or the Septuagint; they may even mix these two sources together to achieve a sort of combined quotation.
- Cross-reference (#vr-xxx). (Example: #xr-gen1:1) A cross-reference is any other passage that is relevant to the passage under consideration, if it is not a direct quote or an allusion.    
- Multiple note insertion (#xxxn:n). (Example: #luk3:1) This tag is a device to apply a note written for one Bible passage to another passage as well. It allows the same note to appear in more than one place.  


Resource-Linking Tags
----------------------

These tags allow the writer to link notes to other project resources, i.e., glossary, articles, etc. 

**THESE TAGS SHOULD BE PLACED AFTER ALL SUITABLE SCRIPTURE-LINKING TAGS HAVE BEEN PLACED.**

- Existing glossary entry (#g-xxx).  (Example: #g-ascension) Use this tag to link the note to an existing glossary item. Check the inventory of current glossary items to see whether the item to which you desire to link already exists; if it does, you will find its approved tag. In that case, then use the same tag.
- Existing article (#a-xxx). (Example: #a-christ) Use this tag to link the note to an existing article. Check the inventory of current articles to see whether the article to which you desire to link already exists; if it does, you will find its approved tag. In that case, then use the same tag.          
- Existing map (#m-xxx). (Example: #m-Judea) Maps are planned to be prepared upon request. They are to be included as a linkable resource.   
- Strongs number (#Hn..., #An..., #Gn...). (Examples: #H0305, #A1933, #G0058) Use these tags to refer to the citation form of a word in a biblical language. These tags should be put in-line in sentences in the notes.  Formatting of the citation should have the English word in square brackets followed by the Strongs number in parenthesis; such as [world](#g2889). Links to Strongs numbers can be found at https://en.wikipedia.org/wiki/Strong%27s_Concordance or elsewhere. Citations with more than one Greek/Hebrew word should list them separately, with each English words followed immediately by the Strong’s link; such as [I](#g1473)[am](#g1510). The user will only see the words enclosed in the square brackets, but those words will link to the Strong’s numbers that follow them.    


    For your information, we expect that glossary entries will look something like these examples:

    #g-ascension - The return of Jesus to heaven after he rose from the dead.

    #g-brother - A male sibling or other close male relative; a fellow member of a group of people--for example, a fellow Christian or a fellow Israelite. In the New Testament, “brothers” can also refer to both men and women in the same group.

    #g-pentecost - A Jewish celebration that came fifty days after the festival of Passover. Pentecost also became an important day in the early church because the believers received the Holy Spirit in a new way on that day. Many Christians consider Pentecost to be the day on which the church formally began.

Workflow Tags
------------

Use these tags in the process of composing and developing the notes. These tags will not appear in the final, publish product. Most of these tags being with (#d...), which you can remember as standing for "desired." 

**THESE TAGS SHOULD BE PLACED AFTER ALL SUITABLE RESOURCE-LINKING TAGS HAVE BEEN PLACED.**

Once a manager-reviser accepts a requested item, he or she will do the following: (a) create a page for the item, (b) run a script changing the #dx- tag to a #x- tag everywhere in the UBN repository, and (c) place the changed tag in the proper tag order. For example, after accepting a request to add "Crucifixion" as a glossary item, the #dg-crucifixion tag will be changed by a script application to #g-crucifixion. And after accepting the request for a map of Egypt at the time of the Exodus, a page for that map will be created, and the #dm-egyptattimeofexodus tag will be changed to #m-egyptattimeofexodus. Finally (d), the manager-reviser will also ensure that these new items be added to the current inventories of items.


This means that for a resource item to be said to exist, it will suffice for that item to have a unique page and a permanent tag—even if the content of that item is not yet written.

- Question (#q).  Use this tag to mark every working question created to generate a note. Place the tag after the question on the same line. (This is an exception to the general rule of each tag sitting in its own line.) 
- Desired glossary entry (#dg-xxx).  (Example: #dg-blessing) Use this tag to request a new item to be added to the glossary. 
- Desired article (#da-xxx).  (Example: #da-crucifixion) Use this tag to request a new article to be written. 
- Desired map (#dm-xxx). (Example: #dm-Jerusalem in David's time) Use this tag to request a new map to be drawn and added to the map resources.   
- Desired biblical theme (#dbt-xxx) (Example: #dbt-verbalinspir) Use this tag to request a new biblical theme that the user can employ for filtering notes.  
- Desired theological stance (#dts-xxx) (Example: #dts-infantbap) Use this tag to request a new biblical theological stance that the user can employ for filtering notes.  

