# jint-bidirectional
This is a Collection of Modules to Compose BiDirectional Tasks between .NET  mostly Windows it gets used to create Windows Bindings with less effort.

## Why?
JInt is a Javascript es5 runtime written in .NET so it is able to bidirectional interface with .NET Apps and .NET Apps by design can Interface Windows API's easy and in a consistent way. 

## Usage
This gets used to Compose Tasks that get executed via the jint-bidirectional .NET component you need to create a net-service-component with that and execute your Tasks in it by default jint-bidirectional-component can be used and runned as windows-service it uses the @stealify/component-manager to schedule Tasks in other Stealify Components and it can get accessed via .NET libs

## Usecases
- connect oldschool .NET apps written in C#, F#, or Visual Basic. to Modern ECMAScript Code es2022 running in current Engines. 
- Reuse existing codes to create bindings to legacy platforms like Windows or any other .NET Supported Platform.
