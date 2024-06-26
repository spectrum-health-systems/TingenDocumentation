# The Script Parameter

## CONTENTS
[Overview](#overview)
[Components](components)
[Syntax](#syntax)

# Overview
The Script Parameter sent from Avatar contains all of the information Abatab needs to do what it needs to do, including:

* The requested `Module`  
* The requested `Command`
* The requested `Action`
* The requested `Option`
<br>

# Script Parameters

## Syntax

Script Parameters have the following syntax:

    `Module-Command-Action-Option`

For example:

    `ProgressNote-VerifyLocation-GroupIndividualNote`

The maximum length of a script parameter is 50 characters.

In general, the full names of the components should be used.

If the full name cannot be used:

* The `MODULE` component is 14 characters, or less
* The `COMMAND` component is 15 characters, or less (see below)
* The `ACTION` component is 15 characters, or less
* The `OPTION` component is 3 characters, or less

`MODULE-COMMAND-ACTION-OPTION`

12345678901234567890123456789012345678901234567890
OpenIncident-Verify-OriginalAuthorIsSubmitting
OpenIncident-Verify-OriginalAuthorIsOpening

* Module: Admin
  * Admin-Service-Update-Mode
  * Admin-Service-Update-CurrentSettings
  * Admin-Service-Update-All

* Module: Open Incident
  * OpenIncident-Verify-OriginalAuthorIsSubmitting
  * OpenIncident-Verify-OriginalAuthorIsOpening

* Module: Testing


## Scr

`Testing-DataDump-SessionInformation`  
`Testing-ErrorCode-ErrorCode1`  

### PROGRESSNOTE
`MODULE__-COMMAND_____-ACTION__________-OP`
`ProgNote-VfyLoc-GroupIndiNote`
`ProgNote-VfyLoc-IndiCounselingNote`  

### QUICKMEDICATIONORDER
`QMedOrdr-vfyAmount-Dose`


## Abbreviations

### Module

Module abbreviations are 8 characters.

* ProgNote = Progress Note
* Proto    = Prototype
* QMedOrdr = Quick Medication Order
* Testing  = Testing

### Keywords

Keyword abbreviations are 4 characters.

* Vfy  = Verify  

### Other abbreviations

* Loc  = Location
* Indi = Individual/Individualized
* Inde = Independent

<br>

***

<div align="center">

  This document is part of the [Abatab Documentation Project](../Abatab%20Documentation%20Project.md).

  <h5>
    Last updated: 230329.1117
  </h5>

</div>
