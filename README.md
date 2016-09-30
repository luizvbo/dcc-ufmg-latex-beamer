#Template for DCC/UFMG Slides

This template is based on the **Unofficial Uppsala theme for Beamer** (http://www.it.uu.se/katalog/daz/uppsala_beamer)

## Instalation

**Adpted from from https://en.wikibooks.org/wiki/LaTeX/Installing_Extra_Packages**

### Install the files

While the documentation is printing, move or copy the package files from your temporary directory to the right place[s] in your TeX local installation directory tree. Packages installed by hand should always be placed in your "local" directory tree, not in the directory tree containing all the pre-installed packages. This is done to a) prevent your new package accidentally overwriting files in the main TeX directories; and b) avoid your newly-installed files being overwritten when you next update your version of TeX.

For a TDS(TeX Directory Structure)-conformant system, your "local installation directory tree" is a folder and its subfolders. The outermost folder should probably be called texmf-local/ or texmf/. Its location depends on your system.
The place to copy the files in the repository is given by:

        MacTeX: Users/username/Library/texmf/tex/latex/*packagename*
        Unix-type systems: Usually ~/texmf/tex/latex/*packagename*
        MikTeX: Your local directory tree can be any folder you like, as long as you then register it as a user-managed texmf directory (see http://docs.miktex.org/manual/localadditions.html#id573803)

### Update your index

Finally, run your TeX indexer program to update the package database. This program comes with every modern version of TeX and has various names depending on the LaTeX distribution you use. (Read the documentation that came with your installation to find out which it is, or consult http://www.tug.org/fonts/fontinstall.html#fndb):

        teTeX, TeX Live, fpTeX: texhash
        web2c: mktexlsr
        MacTeX: MacTeX appears to do this for you.
        MikTeX: initexmf --update-fndb (or use the GUI)
        MiKTeX 2.7 or later versions, installed on Windows XP through Windows 7: Start -> All Programs -> MikTex -> Settings. In Windows 8 use the keyword Settings and choose the option of Settings with the MiKTex logo. In Settings menu choose the first tab and click on Refresh FNDB-button (MikTex will then check the Program Files directory and update the list of File Name DataBase). After that just verify by clicking 'OK'.

