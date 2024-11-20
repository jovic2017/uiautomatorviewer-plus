# UiautomatorViewer-Plus
### Automated script generation and debugging tool based on Uiautomator secondary development. This tool will make you to quickly develop automated scripts without needing to know the code. You just need to generate code based on this tool, and then debug the code through the tool, and the automation script is developed in this way.
### Notice: This tool base on this bdd framework https://github.com/jovic2017/MobileBDD
![image](https://github.com/user-attachments/assets/a171b620-3c2b-4edf-b0a7-739ba7580820)
![image](https://github.com/user-attachments/assets/99f95f65-ee16-4085-9733-5b057770e210)
Next, let's take a look currently implemented functions, from left to right: system settings, Step adding and modifying, waiting for elements to appear, clicking on elements, saving text, input text, adding assertions, deleting nodes, generating code, refreshing test cases and Debug tool
![image](https://github.com/user-attachments/assets/fab44e36-9b54-4387-8059-b07eb5b41163)
### System settings, which can set the generated class names, debug servers, code templates and output paths, and finally test data.
![image](https://github.com/user-attachments/assets/532ade47-d02e-4324-a97e-943afc97c1e1)
### Step addition, modification, and maintenance of public steps. Click on 'My Testing Scenarios' to add new test steps or select common test steps
![image](https://github.com/user-attachments/assets/40913441-9d22-47c3-93a2-1178cd46a716)
### Wait for the element to display. Select the element you want to operate on the screen, and the text of the current element will be displayed by default. If there is no text for the element, use xpath to locate it. The default is to wait for the selected element to appear, or you can choose to wait for the relative element of that element to appear.
![image](https://github.com/user-attachments/assets/8d8aa48d-8772-4aae-912f-583082d3b67d)
### Clicking on an element also uses text positioning by default. You can click on the selected element, or on other relative node elements of that element. You can also set to only click on a certain element when text appears.
![image](https://github.com/user-attachments/assets/da8aec2f-7120-45f5-bc9f-c2b6eb6b6037)
### Save the text. Searching for the target element in the interface can assist you in finding the correct target element. If there is a resource id, it is used for positioning by default. If not, other text relative positioning or custom xpath can be used. Click to find the target element, and the corresponding xpath and target element text will be displayed below. Then enter the key and description information to save the text
![image](https://github.com/user-attachments/assets/b35f3768-c7b5-43b0-b8df-2a50bfbcb317)
### Entering text and searching for the target element in the interface can assist you in finding the correct target element for the text to be entered. Clicking on the input box for the text will bring up the second and third interfaces, allowing you to select the text to be entered
![image](https://github.com/user-attachments/assets/fc3d60d2-0eaf-4cd9-9536-4cdcdc89c510)
![image](https://github.com/user-attachments/assets/6f6c6783-2bec-400d-b7d6-13af4ca0b467)
### Add assertions to compare the elements displayed on the interface with known and determined data. Searching for the target element in the interface can assist you in finding the element that needs to be compared. Click the input box at the bottom to select the expected text from the cache, or click the tab on the right to select the expected text from the test data
![image](https://github.com/user-attachments/assets/e02d748c-df1f-4e2d-8094-94a0cb8e92ad)
### Screen sliding allows you to set the direction, speed, and timeout time of the slide.
![image](https://github.com/user-attachments/assets/9459e2c3-28b9-4072-9284-5e1362124b51)
### To generate code, simply click the "Generate Code" button. The generated code includes a feature file, two Step files (the operations of the two Steps are the same, except that the Step at the end of Debug puts each operation into a separate method, which is only used by Debug tools), a page object Screen, and a multilingual file
![image](https://github.com/user-attachments/assets/3fd437b4-1cd7-4b76-a519-74ff73bcef75)
![image](https://github.com/user-attachments/assets/a670dc05-1c2b-49f0-8c89-bb407c762e93)
![image](https://github.com/user-attachments/assets/46d3de60-0e82-48f0-a1bf-30d72274cc8d)
![image](https://github.com/user-attachments/assets/d7eead3c-bd45-46ae-81fc-fc7b0dd059ce)
### The Debug tool can select a step and debug all operations under this step, or select an operation, click the Debug button to display the pop-up box below, and click Execute to debug the corresponding code. In the custom tab, you can debug any code without debugging the current operation. You only need to specify the class name, method name, and method parameters. If there are any problems, you can check "Print PageSource" to print out the source code of the current screen for inspection.
![image](https://github.com/user-attachments/assets/083ecbaa-ab86-414a-b076-46c01bd881f0)
![image](https://github.com/user-attachments/assets/bb0c68a4-c8e2-449c-ab7b-709a04bc5c2c)




