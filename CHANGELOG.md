# Change Log

All notable changes to the "simpler-flutter-snippets" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

-- FYI
keybindings 
snippets.customLogger - [command + shift + q]
snippets.expanded - [command + shift + e]
snippets.flexible - [command + shift + f]
snippets.emptyWidgetWrap - [command + shift + w]
snippets.rowColumn - [command + shift + c]
snippets.toggleAutoFix - [command + shift + x] - true/false
snippets.removeThisWidget - [command + shift + r]
snippets.singleChildScrollView - [command + shift + s]
ValueNotifierBuilder - [command + shift + v]

## Release Notes
### 0.2.7
  - Fixed the cursor that moved down after the wrapper
### 0.2.6
  - added toggle Auto Fix to apply quick fixers 
   - snippets.toggleAutoFix - keybinding [command + shift + x]
   - deleted auto format
   - added new key bind snippets
    - snippets.emptyWidgetWrap - keybinding [command + shift + w]
    - snippets.rowColumn - keybinding [command + shift + c]
### 0.2.5
  - updated auto IMPORTS when clicking the Widget 
  - added new feature selecting auto quick fix
    - SimplerFlutterSnippets.selectedImport: true
    - SimplerFlutterSnippets.autoFix: true
    - SimplerFlutterSnippets.FlutterImports: {
      - targetFileTypes: ["dart"]
      - importMappings: [
        {
                "imports": [
                    "import 'package:freezed_annotation/freezed_annotation.dart';"
                ],
                "keys": [
                    "freezed"
                ]
            },
      ]
    }
### 0.2.4 
  - added auto IMPORTS when clicking the Widget 
    - SimplerFlutterSnippets.selectedImport = true [restart the vs code]
      - BlocProvider
      - BlocListener
      - BlocBuilder
      - BlocSelector
      - BlocConsumer
      - RepositoryProvider
      - read
      - freezed
      - GetIt
      - HiveType
      - LocaleKeys
      - tr
      - AutoRouter
      - router
      - singleton
      - injectable
      - LazySingleton
      - Singleton
      - Injectable
      - Equatable
      - log

### 0.2.0-0.2.3 (Fixing bugs)
  - little release 
    - added keybinding remove this widget 
      - mac cmd+shift+r
      - winda ctrl+shift+r
### 0.1.9
  - added new Wrappers with auto imports
    - Stack
    - Cubit/Bloc Builder
    - Cubit/Bloc Consumer
  - to snippet "listViewS" add default SIzedBox
### 0.1.8
  - fixed increment the logger
  
### 0.1.7
  - frxr -> Text.rich()
  - wrapeers command + shift + e -> 
    - expanded, 
    - flexible,
    - fittedBox
  - wrapper command + shift + s 
    - SingleChildScrollView
    - Padding  
  - fhiveModel - hive Model
  - fnav cupertino - Navigator - Cupertino
  - changed Log'a String to data-unique

### 0.1.5
  - Changed Log's String -> data to <CopyClipBoard>

### 0.1.4
  - Bug Fixed 
  - Optimized The Extension

### 0.1.3
  - ReWrite Settings
### 0.1.0
  - added logger
    - snippets.customLogger add keybinding

### 0.0.8
  - Wrappers
    - StateFullBuilder
    - AnimatedBuilder
    - StreamBuilder
    - SingleChildScrollViewBuilder

  - Snippets
    - fvalueNotifier
    - freezed
    - frow
    - fcol
    - flist
    - fcolorHax
    - fvalueNotifier
    - fanimatedBuilder
    - fvariable
    - fmap
    - fset
    - fgetarr
    - fsettarr
    - ff
### 0.0.7
  - Tween Builder
  
  - hide / show 
    - on vs code menu
    
### 0.0.3-4-6
  - wrappers
    - ValueListableBuilder
    - FutureBuilder
### 0.0.2
  - Widgets
  - Life Cycle
  - Dop
### 0.0.1

Initial release

**Enjoy!**
