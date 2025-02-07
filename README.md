# COLaF Website Documentation

Welcome to the repository for the [COLaF website](https://colaf.huma-num.fr/). The website is built using the [Hugo Academic Theme](https://github.com/HugoBlox/hugo-blox-builder).

The COLaF website serves as a hub for research outputs, member information, and project updates. It is multilingual, with content available in both English and French.
## Content Updates and Modifications
### Steps for Updating Content
1. **Create a New Branch:**
   Always create a separate branch for your changes to ensure a clean version history.
   
3. **Directory Guidelines:** <br/>
   To do in both content/en and content/fr with the english version of the text in content/en and the french version of the text in content/fr.
   - **Adding new COLaF team members, partners and results**:<br/>
       - Create a new directory in `authors/` such as:
         
| Type of adding                         | Name of new directory         | _index pattern |
|-------------------------------|-------------------|-------------------|
| Add Team Member               | `people-nameOfPerson`        | `documentation/people-index.md`|
| Add Partners laboratories and institutions | `part-nameofPartner` |`documentation/part-index.md`|
| Add Results - new Data/corpus produced |`data-nameofCorpus`|`documentation/result-index.md`|
| Add Results - new tools created | `outil-nameofTool`|`documentation/result-index.md`| 
| Add Results - Work in Progress | `wip-nameofWIP`|`documentation/result-index.md`|

       - Add a file _index.md (available in the documentation) in the new folder, and modify it by following the information in the document according to the person being added.
       - Add a profil picture in the directory named `avatar.jpg`

6. **Open a Pull Request:**
   Create a pull request on the repository to merge your changes.
   
By following these guidelines, you ensure that the website remains organized and up-to-date. Thank you for contributing to the COLaF website!



 
