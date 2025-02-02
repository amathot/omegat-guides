# Proofreading

**OmegaT** is the open source computer-assisted translation tool (CAT tool) which will be used to translate, reconcile, adapt, review and verify materials. The software has been customized to enable you to perform your task. 

## Quick walkthrough for proofreading

  * Download the OMT package and the Excel file containing the translation and adaptation guidelines from Plunet.
  * Import the OMT package in OmegaT. To see how to do so, please read the section [Accessing the package for the first time](/doku.php?id=ug:omt-pack). 
  * Create the target files for preview on the portal. To see how to create the files, please refer to the section [Creating target files](/doku.php?id=ug:omt-targets)
  * Connect to the PISA portal with the credentials provided in the dispatch mail: [PISA PORTAL](https://pisa.ets.org/)
  * Go to the **Translations** TAB

![](../_assets/img/portal_tra_tab.jpg)

  * Drag and drop the target XLIFF you wish to preview and press the **Preview chosen XLIFF** Button
  * The XLIFF for preview in your language opens. You can also preview the source text by clicking on **Preview eng-ZZZ button**

![](../_assets/img/portal_preview.jpg)

  * Read the items in your language on the portal. Focus on the following:
    * Fluency
    * Grammar & Typos
    * Punctuation
  * To navigate from one screen to the other and read through the full item press the "Next" arrows on the screen

![](../_assets/img/portal_next_arrow.jpg)

  * If you notice something you wish to correct, copy the sentence/part of the sentence in your language from the preview
  * In OmegaT, press ++ctrl+f++ on your keyboard. The search dialog opens.
  * Paste the sentence/part of sentence you copied from the portal and press the Search button.

![](../_assets/img/proof_search.jpg)

  * Double click on the result to go to the appropriate segment in OmegaT. In the screenshot below, the segment number is 40

![](../_assets/img/proof_segment.jpg)

  * Before you make any changes, double check in the Excel file if there is no guideline for that segment, or if there is no comment from the reconciler. The changes you make cannot contradict a guideline or the reconciler's decision. If you are in a case where you believe something should be changed and it goes against the guidelines, please send us an e-mail to explain the situation.

Repeat this process for all files in your batch.

  * When you are done, create the target OMT package for delivery [Delivering the project](/doku.php?id=ug:omt-exp-pack) and upload it on Plunet together with the Excel for documentation. 

## Accessing the package

### Accessing the package for the first time

The following steps need to be performed __only once per OmegaT package__: when you access each package for the first time: 

1. Download the  from the portal

2. Store the  in a location you will remember on your computer. 

3. Import the  in OmegaT: 

  * Open OmegaT
  * Go to **Project>Import OMT package**

![](../_assets/img/01_import_omt_package.jpg)

  * Navigate to the location where you stored the OMT package. Choose the  and click on Open

![](../_assets/img/02_open_omt_package.jpg)

  * A pop up opens. Click **Yes**.

![](../_assets/img/03_delete_original_package.jpg) 

4. Translate/Reconcile/Adapt/Review the files in the package.

When you are done working for the day, close OmegaT.

### Access the package after import

The next times you want to access the project in OmegaT, go to **Project>Open Recent Project**. The project you were working on is the first one in the list:

![](../_assets/img/04_open_recent_project.jpg)

## Navigation

### Navigation between the different panes

When you open OmegaT you will notice the screen is split in several panes:

  * The **Editor pane** is the main pane in which you will be working.
  * Translation suggestions will appear in the **Fuzzy Matches pane**.
  * The **Glossary pane** will display the existing glossary entries and the ones you may add.
  * The **Multiple Translations pane** will show you if a repeated segment was translated differently.

![](../_assets/img/05_omegat_panes.jpg)

### Navigation between the different files

If the project contains multiple files, they are listed in the **Project Files pane**. The file currently open is highlighted in blue.

![](../_assets/img/06_project_files_pane.jpg)

If you want to open a different file in the Editor pane, click on it in the Project Files pane. You can also see the name of the file that is open in the Editor pane's title bar.

### Navigation between the different segments

In the editor pane, the active segment is highlighted in green. This is the segment you are working in. The translation is displayed right below the source text. 

Press the **Enter** key on your keyboard to go to the next segment. A segment can also be activated by double clicking on it. It then becomes green.

![](../_assets/img/07_active_segment.jpg)

In OmegaT, a **color code** will help you find your way around between the different segments:

  * **Green** = the segment you are working in (active segment)
  * **Grey** = translated segment. The translation is displayed below the source text.
  * **Orange** = pretranslated and locked segment (e.g. trend). These segments cannot be edited in OmegaT. 

All segments should appear translated in a project for proofreading. If you notice an untranslated segment in ****, please contact cApStAn's project managers to see how it should be handled.

![](../_assets/img/08_color_coding.jpg)

### Recognizing tags

If you are in a segment which contains tags, you will recognize them because they are in **red font**. 

![](../_assets/img/09a_tags_recognizing_ada.jpg)

There are two types of tags - standalone tags and double tags:

  * **Standalone tags** = a single tag with a precise role (e.g. <br/> tag which introduces a new paragraph in HTML)
  * **Double tags** are composed of an opening and a closing tag, such as the HTML tags for making text bold, italic, underlined, etc. **Double tags** affect the text between them and you need to ensure they are positioned around the exact same words in the source and in the translation.

![](../_assets/img/10_types_of_tags.jpg)

### Fixing tag issues

For your language task, all tags should be present in the translation. What is important is to correct potential errors that you may see. In the screenshot below, in the source segment the **** are around the letter **"n"** while in the target they are around the word **"which"**. 

![](../_assets/img/09b_tags_issue_ada.jpg)

To correct this issue, you would have to perform the following steps:

  * **double click** on the first incorrectly inserted tag in the target segment to select it and press **Backspace** on your keyboard to delete it 
  * repeat the operation until you deleted all incorrectly inserted tags
  * place your mouse where the first tag should be correctly inserted and press ++ctrl+t++ on your keyboard to insert the first tag
  * insert all other missing tags.

![](../_assets/img/11a_tag_order_ada.jpg)

Please note that tags are inserted in the order of their appearance in the source segment.

## Handling repeated segments

Some segments are identical to each other. They are called “**repeated segments**” and their translation is __autopropagated__. 

### Identifying repeated segments

You can recognize that you are in a repeated segment because it has gray font.
When a repeated segment is active, the segment number will indicate how many repetitions exist: 

![](../_assets/img/15_repeated_segment.jpg)

If you **right click** on a repeated segment, the contextual menu will point out the other occurrences of a repeated segment. It can be useful to jump to them (by selecting them from the contextual menu) to see the different contexts in which a repeated segment appears.

![](../_assets/img/16_repeated_context.jpg)

### Autopropagation

If you edit the translation of a repeated segment, by default, the changes will be automatically reflected in all the repetitions. This happens in the same file, but also in all the files of the OmegaT package.

![](../_assets/img/17_autopropagation.jpg)

### Create alternative translation

In some cases, you may not wish to modify the translation of all repeated segments. Due to a different context, you may need to change only ONE of the repeated segments:

  * **Right click** on the segment 
  * Choose **Create Alternative Translation** from the contextual menu

![](../_assets/img/18_create_alternative_translation.jpg)

  * Change the translation of your active segment and then either press ++ctrl+s++ or move to the next one.

![](../_assets/img/19_alternative_translation_created.jpg)

If you return on the repeated segment, you will see the different translations appear in the Multiple Translations pane.

## Other useful features

### Using the character table

**Special characters** can be inserted with the Special Characters Table. Special characters can be:

  * quotation marks: «», „“, ‘’, etc. 
  * mathematical symbols: ×, π, ÷, ≤, ≠, √, etc. 
  * other characters: ®, ™

When you arrive in a segment in which you need to insert a special character, perform the following steps:

  * Press ++ctrl+space++ on your keyboard several times until you reach the special characters table.

![](../_assets/img/25_character_table.jpg)

  * Select the character you want to insert
  * Press **Enter** and continue editing your segment.

![](../_assets/img/26_inserted_special_characters.jpg)

### Inserting non-breaking spaces

In order to insert non-breaking spaces in OmegaT, please make sure you have installed **Auto Hot Key**. If you haven't installed it yet, please check the **Third Party Tools** section of the [OmegaT Installation guide](/doku.php?id=ug:tec-cb-ome-ins)

Once **Auto Hot Key** is installed, you can insert non-breaking spaces with the same keyboard shortcut as in Word: ++ctrl+shift+space++. You can recognize a non breaking space because it is gray. 

![](../_assets/img/27_non-breaking_spaces.jpg)

### Performing concordance searches

A concordance search allows you to look for words and expressions in the translation memory and the glossary. To perform a search follow the steps below:

  * In the active segment, select the word you want to search for with your mouse.
  * Press ++ctrl+f++ on your keyboard.
  * The Search window will open.
  * Press Search. 
  * The results will be displayed.
  * You can copy (select with mouse and press ++ctrl+c++ on your keyboard) what you need from the results and paste it in the target translation at the right place.

![](../_assets/img/38_concordance_search.jpg)

**TIP:** There might be small differences (in punctuation, spacing, etc.) between the text you're searching for and other occurrences of the same text that would prevent an *exact match*. The option "Keyword search" might help overcome that problem, please use it if you don't get the results you were expecting.

## Performing QA checks in OmegaT

### Completion check

All segments of the OmegaT package must have a translation. To ensure that is the case, please check for completion prior to delivery:

  * Go to **Project>Project Files**
  * The project files pane will open
  * **OK:** If the **Number of unique segments** __is equal to__ the number of **Translated unique segments**.

![](../_assets/img/32_completion.jpg)

  * **NOT OK**: the **Number of unique segments** __is different from__ the number of **Translated unique segments**. To correct: 

  1. Close the Project Files Pane
  1. Press ++ctrl+u++ on your keyboard to jump to the __Next Untranslated Segment__. 
  1. When the cursor stops moving from the active segment then all segments have a translation.

Recheck for completion, to make sure by opening the Project Files pane.

### Check and fix tags

To ensure that all tags have been inserted correctly:

  * Go to **Tools>Check Issues**. A pop up window will open.

![](../_assets/img/33_check_issues.jpg)

By default, other types of checks (Spelling, Terminology, LanguageTool) are ticked. If you want to check for issues related to tags before performing the rest of the checks, you can untick them. You will notice that the **Tag Issues** box cannot be unticked.

  * Press **OK**.
  * An error report will open.

![](../_assets/img/34_error_report.jpg)

  * Go through the issues one by one:

  1. Correct the issue by clicking on **Jump to Segment**. 
  1. You will arrive at the appropriate segment in the editor pane. 
  1. Place your cursor where the missing tag needs to be inserted and press ++ctrl+t++ to insert the missing tag.
  1. Press Enter to move to the next segment.
  1. Open the Error report again. It has automatically refreshed.
  1. Finish going through the issues.

**TIP**: If in the source there are tags that you do not use in your language which are present in the source segment, to avoid having false positives in the error report, you can insert them at the end of the segment. They would not have an impact on any text.

!!! caution
    Please do not click on "Apply fix", fix each issue manually.

## Creating target files

Press ++ctrl+shift+d++ to create the target file you were working on. This will allow you to preview the translated file with your changes.

To access the file, go to **Project>Access Project Contents>Target Files**. A window with the contents of the "target" folder will open. Find the file you were working on, if there are several files and preview it to read the translation in context.

![](../_assets/img/28_target_files.jpg)

## Delivering the project

Once you have finished editing the OmegaT package and have performed the appropriate Q&A checks, you need to Export the .

  * Go to **Project>Export OMT Package**

![](../_assets/img/29_export_omt.jpg)

  * A pop up window will open.
  * Click Save
  * Press OK in the Pop-up window notifying that the package was successfully created.

![](../_assets/img/30_omt_successful.jpg)

  * You will be automatically directed to the location the exported package is stored.
  * You will recognize the package because it has the extension OMT. It should be the 4th from the bottom.

![](../_assets/img/31_recognizing_omt.jpg)

This is the file you have to deliver.

<!-- section: shortcuts -->
{% include 'cheatsheet.md' %}