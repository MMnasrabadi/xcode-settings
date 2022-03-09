My XCode
---
    1.Settings 
    2.Key Bindings 
    3.Font And Color Themes 
    4.CodeSnippets
    
    5.IDETextKeyBindingSet.plist

UserData
--- 
    UserData is exported Xcode settings.
    Place at ~/Library/Developer/Xcode/UserData




IDETextKeyBindingSet
---
    IDETextKeyBindingSet.plist  makes available custom key bindings.
    
    Place at /Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Versions/A/Resources/IDETextKeyBindingSet.plist.
	-- OR --
	$ sudo sh IDETextKeyBindingSet.sh 


 
 
Help-full
---
    show hidden to mac 
        defaults write com.apple.finder AppleShowAllFiles YES;
        killall Finder /System/Library/CoreServices/Finder.app
    And off 
        defaults write com.apple.Finder AppleShowAllFiles false
        killall Finder

    gitkraken show . file hidden
        Shift + Cmd + .  TO REPO SELECTION
    
