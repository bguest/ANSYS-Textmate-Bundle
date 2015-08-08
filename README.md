EDIT: You can use E Text Editor on windows along with the ANSYS-Textmate-Bundle.

INSTALATION:

To install for TextMate (in terminal.app):
	mkdir -p ~/Library/Application\ Support/TextMate/Bundles
 	cd ~/Library/Application\ Support/TextMate/Bundles
 	git clone git@github.com:bguest/ANSYS-Textmate-Bundle.git ANSYS.tmbundle
 	
To install for E-TextEditor (in git bash):
	mkdir -p ~/Application\ Data/e/Bundles
	cd ~/Application\ Data/e/Bundles
	git clone git@github.com:bguest/ANSYS-Textmate-Bundle.git ANSYS.tmbundle

Note: in order to get proper syntax highlihgting you will probably want to add colors 
for the following scopes:

keyword.star.apdl (*commands)
keyword.command.apdl (regular ansys commands)
keyword.argument.apdl (stuff like 'all','s','volu')
keyword.macro.apdl (My local ansys macros); 

    Note:you will also have to edit the bundel to get your macros to be highlighted

###Story:

Ok, Imagine for a second that you are an mechanical engineer plagued with the horror of
being forced to use Windows XP day after day. Why do you have to use Windows XP?!?!?! 
Simple, because the only software that you can use to get your job done is ANSYS and it
seems to run best on Windows. Now imagine that you don't want to be chained to your
desk 8 hours a day 5 days a week. Simple right, install ANSYS on your laptop and you're
good to go... Well not really, being the highly evolved person that you are, you bought
at Mac. Thankfully there is a solution, Paralles, yeah, probably not ideal for number
crunching, but it gets the job done.

Now that you are all set up using ANSYS on your mac, life is good, but there is just
one problem, what text editor do you use? You could use your old windows text editor
with parallels as well... Or you could use Textmate, the software that is partially
responsible for your love of macs and hatred of windows. Unfortunately there is not an
ansys bundle. Fortunately I created one.

### LICENCE

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
