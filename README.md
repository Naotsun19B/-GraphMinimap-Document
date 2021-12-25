# GraphMinimap

![Plugin](https://user-images.githubusercontent.com/51815450/147378061-05e7c9d0-488a-4e9c-bfdf-bb1966bb5fb1.PNG)

<!--ts-->
* [Description](#Description)
* [Requirement](#Requirement)
* [Installation](#Installation)
* [Features And Usages](#features-and-usages)
    * [Hidden](#hidden)
    * [Resizable](#resizable)
    * [Visible](#visible)
    * [Controllable](#controllable)
* [Settings](#Settings)
* [Author](#Author)
* [History](#History)
<!--te-->

## Description

This plugin adds a minimap to the graph editor that gives you an overview of the entire graph.  
You can also operate the graph editor from the minimap.  

## Requirement

Target version : UE4.24 ～ 4.27 (UE5.0EA)    
Target platform : Windows, Mac, Linux  

## Installation

IN PREPARATION  

## Features And Usages

It supports basic graph editors such as blueprint and material, etc.  
The minimap is automatically displayed when you open the graph editor.  
You can switch the minimap mode with the shortcut key.  
The default shortcut key is ```Shift + Ctrl + M```.  
The minimap mode and size are saved for each graph and will be restored the next time you open the graph editor.  

### Hidden

The minimap is hidden.  

### Resizable

![Resizable](https://user-images.githubusercontent.com/51815450/147378312-897bc859-d8ae-4587-a393-a1ac4ccc471b.gif)

You can resize the minimap by dragging.  
You can also resize the minimap by scrolling the mouse.  

### Visible

![Visible](https://user-images.githubusercontent.com/51815450/147378411-a44fcdc6-9bd5-44aa-8a09-5f1c0769f87f.gif)

There is no collision detection on the minimap, and you can operate the graph editor through the minimap.  

### Controllable

![Controllable](https://user-images.githubusercontent.com/51815450/147378422-be90a3b0-a9bd-40a8-a6b5-f7a931d5dd2d.gif)

You can move the camera position of the graph editor by dragging.  
You can zoom with the mouse scroll.  

## Settings

![ShortcutKeySettings](https://user-images.githubusercontent.com/51815450/147378158-5c75649f-88e6-4f6d-9af9-cf0ac07ef649.PNG)

The shortcut keys introduced in "Functions And Usage" can be changed from the keyboard shortcuts in the editor environment settings.  

![Settings](https://user-images.githubusercontent.com/51815450/147378165-9eeb0cd2-9247-47cd-873c-dcf59eb57500.PNG)

|**Category**|**Item**|**Description**|
|---|---|---|
|Default State|Default Graph Minimap State|The default minimap state used when the minimap state is not cached.|
| |Default Graph Minimap Size|The size of the minimap to display on the graph editor.|
| |Keep Graph Minimap State|Whether to restore the state of the minimap for each graph at the next startup.|
| |Clear Cache File Button|A button to delete the cached minimap data.|
|Limitation|Max Graph Size|Maximum size of graph that can be drawn in the minimap.\nIf set it too high, you may run out of video memory and crash.|
|Minimap|Minimap Alignment|The position on which the minimap is displayed in the graph editor.|
| |Minimap Opacity|The opacity of the minimap to display on the graph editor.|
| |Minimap Tint Color|The tint color of the minimap to display on the graph editor.|
| |Mode Icon Size|The size of the mode icon displayed in the upper left of the minimap.|
| |Padding|The size of the margin applied when drawing the graph.|
| |Mode Icon Tint Color|The tint color of the mode icon displayed in the upper left of the minimap.|
| |Camera Bounds Color|The color of camera bounds displayed on the minimap.|
| |Camera Bounds Thickness|The thickness of camera bounds displayed on the minimap.|
| |Drag Sensitivity|The mouse sensitivity when dragging.|

## Author

[Naotsun](https://twitter.com/Naotsun_UE)

## History

- (2021/12/25) v1.0   
  IN PREPARATION