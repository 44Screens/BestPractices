# 3D Assets Best Practices

## Table of Contents

1. [Introduction](#introduction)
2. [Pivot Point](#pivot-point)
3. [Hierarchy](#hierarchy)

## Introduction

## Pivot Point

It's mandatory to check the good positioning of the pivot point for each asset. The pivot point should be in the center of the mesh and in no case outside of it. See the example bellow:

![pivot_point](Images/pivot_point.jpg)

In certain cases, you can move the pivot point at the bottom of the object. It can be useful if we need to position it on a surface later. For example, a plate should have its pivot point at the bottom because in the end, it will be positioned on a table. See the example bellow:

![pivot_point-2](Images/pivot_point-2.jpg)

## Hierarchy

One way to facilitate assets importation is to organised the hierarchy of the file correctly when exporting a UnityPackage. 
In general, you should follow this pattern :

->3D Assets (folder)  
-->*Name of your file* (ex: *Bells*) (folder)  
--->Your content (folder or file)  
--->Your content (folder or file)  
--->Your content (folder or file)  

In Unity, it should looks like this: 

![assets-hierarchy](Images/assets-hierarchy.jpg)