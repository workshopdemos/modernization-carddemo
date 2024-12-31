# Code4z Assistant - Workshop Scenarios

## Initial Setup

The Code4z Assistant extension is used for this workshop. It is already installed and configured in your Code4z Assistant VS Extension.

To open the Code4z Assistant view, click its icon in the activity bar:  
<img src='diagrams/code4z_assistant/activity_bar_assistant_icon.png' width='36pt'/>

This opens the following view:

<img src='diagrams/code4z_assistant/initial_assistant_view.png' style='min-width: 200pt; max-width: 300pt;'/>

The workshop environment is already configured to connect with the Code4z Assistant service. To close the configuration,  click the **X** button.

## Scenario 1: Code Explanation

The Code4z Assistant extension can explain COBOL code in a human-readable way. It uses natural language processing and machine learning techniques to generate explanations for the code.

You can explain sections of a program or entire programs.

Follow these steps:

1. Select a COBOL program from the Explorer view. For example, navigate to: `MODERNIZATION-CARDDEMO` / `app` / `CBACT01C.cbl`.

    <img src='diagrams/code4z_assistant/explorer_open_cobol_program.png' style='min-width: 300pt; max-width: 600pt;'/>

2. To select all code, click inside the editor, then press `⌘`+`A` on macOS or `Ctrl`+`A` on Windows.  
    <img src='diagrams/code4z_assistant/select_all_code.png' style='min-width: 300pt; max-width: 600pt;'/>  
   The selected code is displayed in a panel on the right side of the VS Code window.
   
3. In the Code4z Assistant view, Type `Explain` and press Enter.
    <img src='diagrams/code4z_assistant/chat_explain.png' style='min-width: 200pt; max-width: 400pt;' />
   Code4z Assistant provides an explanation of the selected code in English.  
    <img src='diagrams/code4z_assistant/explain_result.png' style='min-width: 200pt; max-width: 400pt;' />

4. Ask follow-up questions as required. You can also select a specific part of the code and repeat the explanation process to focus on that part. To add the selected code to the chat, press  `⌘`+`L` on macOS or `Ctrl`+`L` on Windows.  

    <img src='diagrams/code4z_assistant/explain_snippet.png' style='min-width: 300pt; max-width: 600pt;'/>

Please share your feedback for Scenario 1:

- Was the information provided accurate and useful?
- What parts of the code would you use the explanation on?

## Troubleshooting Tips

If you notice that progress has stalled in VS Code, try refreshing the window:

1. Press F1 to open the **Command Palette**
2. In the Command Palette, type `Reload Window` and press Enter.
   The VS Code window reloads.


