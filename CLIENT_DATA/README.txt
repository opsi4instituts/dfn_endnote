The initial version of this package was created by Eric Esser, Wissenschaftszentrum Berlin für Sozialforschung (Berlin Social Science Center) and published at the DFN-Repository of the initiative OPSI4instituts: https://opsi.wzb.eu
Contact, questions and suggestions: eric.esser@wzb.eu / opsi@wzb.eu

REQUIREMENTS
------------
- Possession of a site license file of Endnote

HOWTO
-----
1. Install the package on the OPSI server on the command line by "opsi-package-manager -i -p ask dfn_endnote_<Versions-/Paketnummer>.opsi".
2. After the installation copy your "License.dat" file in the "custom" directory in the project folder of the product on the OPSI server.
3. If appropriate, a msi transform file (.mst) can be put in the custom folder as well to customize the installation. It can be integrated by by typing the name of the file in the property "transform-file".


PROPERTIES
----------
* forcereinstall: Force reinstall of complete base package if already installed instead of update. 
* desktopicon: Generate or delete desktop icon.
* transform-file: The name of a mst file located in custom folder to customize the installation.
* fftuseisilinks: Select or deselect the “Web of Knowledge Full Text Links” check box. Please check the EndNote manual for further information.
* fftusedoi: Select or deselect the "DOI" check box. Please check the EndNote manual for further information.
* fftusepubmed: Select or deselect the “PubMed LinkOut” check box. Please check the EndNote manual for further information.
* fftuseopenurl: Select or deselect the “OpenURL” check box. Please check the EndNote manual for further information.
* fftopenurlresolver: URL for the “OpenURL Path” text box. Please check the EndNote manual for further information.
* fftauthenticateurl: URL for the “Authenticate with URL” text box. Please check the EndNote manual for further information.
* installallcontentfiles: Customize the installation via properties in opsi config editor (instprop) or via transformation file (.mst) in custom folder.  Please check the EndNote manual for further information.
* usercanapplyupdates: Let user apply updates.  Please check the EndNote manual for further information.
* custom-post-install: Define filename for include script in custom directory after installation.
* custom-post-deinstall: Define filename for include script in custom directory after deinstallation.
* remove-old-versions: Remove earlier installed versions of Endnote on this machine
* checktask-fatal-error: Set script to fatal error if running office programms are found. Otherwise the script ends, but the product stays on setup. Feature for software-on-demand.
* checktask-show-dialog: Show dialog to the user which office program prevents the installation of Endnote. Feature for software-on-demand.
