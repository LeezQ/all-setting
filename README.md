my sublime user setting file
===============

### for sublime text2

	import urllib2,os; pf='Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler( ))); open( os.path.join( ipp, pf), 'wb' ).write( urllib2.urlopen( 'http://sublime.wbond.net/' +pf.replace( ' ','%20' )).read()); print( 'Please restart Sublime Text to finish installation') 

### for sublime text 3

	import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())

===

### Some Usefull Plugin 

1. emmet : zencoding  
    使用 emmet 时，现在已经换成了html5文档模式，即一些标签不需要闭合，比如 img 、 br 等，但是会引起一些问题，比如 htmlhint 的时候，所以还是建议改成 xhtml 文档模式，方法：Sublime Text -> Preference -> Browse Packages -> Emmit -> Emmet.sublime-settings； 查找 xhtml ，把注释的去掉就好了。  
2. SideBarEnhancements : 侧栏右键功能增强工具  
3. SublimeLinter : 代码检测  
4. LiveReload : 自动刷新，需要配合 chrome 
5. DocBlockr : 注释
