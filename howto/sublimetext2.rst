Configuració del Sublime Text 2
===============================

Instalar el Sublime Package Control
-----------------------------------
Per a un millor control dels plugins, podem instal.lar una funcionalitat nova al Sublime que controla i administra els plugins::
    
    http://wbond.net/sublime_packages/package_control/installation

 1. Obrir el SublimeText2.
 2. Activar la consola.
 3. Copy&paste::

    import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'

 4. Reiniciar el SublimeText2.
 5. Ara, podrem accedir al menú d'instal.lació de plugins nous a través del menú ràpid "super+shift+p" i escriure control. Això limitarà les comandes a les comandes del Package Control.
 6. Escollir la comanda que toqui (Install, Remove, List, ...)

Instalar paquets bàsics
-----------------------
Amb la comanda "super+shift+p" i amb el Package Control, instal.lar els següents plugins:

 * BracketHighlighter
 * SublimeCodeIntel
 * WordHighLight
 * ClipboardHistory
 * Git
 * GitSidebar

Tots són configurables des del menú d'opcions.

Plugins "a manija"
------------------
Decarregar, via Git:

 * https://github.com/vorushin/sublimetext_python_checker.git
 * https://github.com/buymeasoda/soda-theme/

Plugins del Dropbox
-------------------
Copiar des de la carpeta compartida del Dropbox de GC:

 * Zope
 * Buildout

Configuració d'usuari
---------------------
Configurar a partir d'aquí a gust de cadascun. Hi han configuracions base a la carpeta User del Dropbox. Podeu copiar els següents fitxers "a pèl":

 * Base File.sublime-settings
 * Python.sublime-settings
 * *.sublime-snippets
 * Default{plataforma}.sublime-keymap

Instal.lar la command line
--------------------------
Util per obrir fitxers en el editor des de linia de comandes.

Linux::

    ln -s "{Path en el que tinguem el sublime}/{binari del sublime}" /bin/slt

MacOSX::
    
    http://www.sublimetext.com/docs/2/osx_command_line.html

::

    ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" /bin/slt

