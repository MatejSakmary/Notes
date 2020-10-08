## This is basic graph
```mermaid


graph LR;

%% Class Definitions
%% =================

classDef FixFont font-size:11px;

%% Nodes
%% =====

QuickStart(Quick Start):::FixFont -->
    CmdPalette(Command<BR>Palette):::FixFont;
QuickStart --> 
    CreateNotes("Create notes"):::FixFont;
QuickStart --> 
    InternalLinks("Internal Links"):::FixFont;

click CreateNotes "/Create notes";
click CmdPalette "/Command palette";
click InternalLinks "/Internal link";

%% Internal links
%% ==============

class CmdPalette internal-link;
class CreateNotes internal-link;
class InternalLinks internal-link;


 ```