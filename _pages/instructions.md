---
layout: page
title: Instructions
permalink: /instructions/
---
**How to create an incipit page**

Each incipit will need to have its own file within the texts folder in the repository.

Use the information about the composition found in your spreadsheet and then look up the same edition in JumboSearch in order to confirm the citation details, including:
- full title
- editor (if provided)
- call number
- publisher
- publication date
- call number
- stacks location (e.g. Music Library Stacks; Music Library Oversize)
- permalink to the catalog record

Additional editions information
- If there is a digitized edition available in IMSLP, HathiTrust, etc., add the link below the citation as shown in the template below.


**Template for MEI Incipit Page**

At the top of each incipit page you need to include these five elements:
---
- layout: mei
- title: Title of Composition
- author: Composer Last Name, First Name
- permalink: /last-name-short-title or opus/number/
- document: mei filename
---

- Type in the citation details about this composition based on the exact score used to create the incipits. Start the citation with "In" and use an asterisk * around the title to italicize it.
- Add a link to Primo, the stacks location, and call number ''<a href="Primo Link" target="_blank"><Music Library Stacks Call Number></a>''
- If a digital edition is available link to it and identify website/name of site. Type in: "Other editions available in <a href="external link" target="_blank">enter the name of the site here</a>"

View an [example](https://github.com/annakijas1/rebalancing-music-canon/blob/main/_texts/beach-op015_no1_in_autumn.md) of an MEI incipit page

---

**Example of an MEI Incipit Page**

---
- layout: mei
- title: In Memoriam Zach Walker
- author: Anderson, T.J.
- permalink: /anderson-in-memoriam/
- document: anderson_in_memoriam_zach_walker.mei
---

- In *In memoriam Zach Walker* New York: American Composers Alliance, 1968.
- <a href="https://tufts-primo.hosted.exlibrisgroup.com/permalink/f/bnf7qa/01TUN_ALMA21104821390003851" target="_blank">Music Library Oversize M1245.A52 I5 1968</a>

**Tips**

When there is an editor of a volume, add editor's name following the title before the publisher info.
- For [example](https://github.com/annakijas1/rebalancing-music-canon/blob/main/_texts/beach-op015_no1_in_autumn.md): In *Music for piano. II,* edited by Sylvia Glickman. Bryn Mawr, Pa.: Hildegard Pub., 1997.

**How to name files**
- Use all lowercase letters (e.g. anderson_in_memoriam_zach_walker.md)
- Do not include accents/diacritics (e.g. leon.md)
- *Composer page* should use lowercase letters without any accents (e.g. carreno.md)
- *MEI filename* should use underscores and end in .mei (e.g. anderson_in_memoriam_zach_walker.mei)
- *MEI incipit page* should use a hyphen after the last name followed by underscores and end in .md (e.g. anderson-in_memoriam_zach_walker.md)
  - If a title includes an opus number, work number (etc), include the numbers following the last name but before title in the filename. For example: beach-op015_no1_in_autumn.md
- *PNG files* should use hyphens between last name and title (e.g. anderson-minstrel-man.png)

**Where do files live?**
- _texts: all composer page files and incipit page files go into the texts folder

- assets/mei: all mei incipit files go into the mei folder

- assets/images: all png files go into the images folder (when using image instead of mei file to render notation)
