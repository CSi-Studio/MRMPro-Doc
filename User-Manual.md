### Test UserId/Password: Demo/Demo

#### 1.  Prepare analysis data
Prepare mass spectrometry data in vendor formats, such as .wiff. raw .d.
#### 2. Mass spectrum data conversion
Vendor mass spectrometry files need to be converted by **AirdPro** before** MRMPro** analysis. Each original sample will be converted into a pair of **.aird & .json** files,  .aird files store the sorted and compressed mass spectrometry data, and json files store the index information of the data.

1. Open AirdPro software and click on "Conversion"
![image.png](https://cdn.nlark.com/yuque/0/2023/png/240744/1676187785107-f00721f2-b401-4006-a7e1-fafbffe3962c.png#averageHue=%23dfdfdf&clientId=u0b5f3a6c-3e50-4&from=paste&height=890&id=u6cfc7a84&originHeight=890&originWidth=1511&originalType=binary&ratio=1&rotation=0&showTitle=false&size=21993&status=done&style=none&taskId=u83d1d20f-4d70-4169-b1c1-ac178e989e8&title=&width=1511)
2. Select the original file that you want to convert, or select the folder where the converted file is stored, to begin the conversion.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1687916453436-3fb998ac-c434-4d2d-8799-20af4f3d48ed.png#averageHue=%23dcdbdb&clientId=ubf5c6889-e7d0-4&from=paste&height=743&id=ub77cb801&originHeight=743&originWidth=1544&originalType=binary&ratio=1&rotation=0&showTitle=false&size=22650&status=done&style=none&taskId=uba0a4357-5f3a-43fb-a94d-eba0ee553d6&title=&width=1544)
   1. Click the import button, select the file or folder to be analyzed in the pop-up window, select the type of file to be converted, select "MRM", specify the aird file output path, click "Add" button or "Add and Close" to return to the main page, and click "Start" button to start the conversion.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691486195884-124f0918-5299-4c27-953d-f9f61525faa0.png#averageHue=%23e6e3e2&clientId=u030831e2-9b97-4&from=paste&height=879&id=ufcc573a8&originHeight=879&originWidth=1566&originalType=binary&ratio=1&rotation=0&showTitle=false&size=130206&status=done&style=none&taskId=u82e5e64f-eaef-48eb-a9bd-e92471718aa&title=&width=1566)

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691486271959-d77a4dda-34be-4e32-8b00-7db18ae0d681.png#averageHue=%23d9d7d6&clientId=u030831e2-9b97-4&from=paste&height=746&id=u55d72190&originHeight=746&originWidth=1565&originalType=binary&ratio=1&rotation=0&showTitle=false&size=60390&status=done&style=none&taskId=u7206b550-4dae-41a7-abb5-082ca4243b4&title=&width=1565)
3. If you need to speed up, you need to change the conversion configuration, turn off the compression kernel prediction function, and manually set the compression mode based on the characteristics of the data or the previously predicted results.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691486303616-cb20805c-bf10-4d14-b17f-a4dbdd749094.png#averageHue=%23e9e7e6&clientId=u030831e2-9b97-4&from=paste&height=745&id=u9ddade2d&originHeight=745&originWidth=1565&originalType=binary&ratio=1&rotation=0&showTitle=false&size=94113&status=done&style=none&taskId=u4ee6050c-a5f9-4fd6-9b5c-f01f9f83236&title=&width=1565)

When submitting a conversion task, select the newly created configuration to speed it up
![image.png](https://cdn.nlark.com/yuque/0/2023/png/240744/1676188718799-a3200928-0234-4c72-994a-ec5ed93ce2a1.png#averageHue=%23e3e2e1&clientId=u0b5f3a6c-3e50-4&from=paste&height=730&id=u970416c0&originHeight=730&originWidth=1570&originalType=binary&ratio=1&rotation=0&showTitle=false&size=116771&status=done&style=none&taskId=ua420d17d-4156-482a-8337-4cbee32b8d0&title=&width=1570)

#### 3. User login
MRMPro supports user login, email registration login and mobile number login.
Trial account: user: demo password: demo
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691486472767-a3e43f9b-d7df-41ec-a1d9-fd4411c4a791.png#averageHue=%23f8f8f8&clientId=u030831e2-9b97-4&from=paste&height=472&id=u8b55bb50&originHeight=472&originWidth=638&originalType=binary&ratio=1&rotation=0&showTitle=false&size=21224&status=done&style=none&taskId=u02cd577e-933b-4875-aff1-12294190ecf&title=&width=638)
#### 4. Create a project

1. Click "Create" on the "Project" page.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691486623408-745fc9df-efda-4243-8387-a245fa219ffa.png#averageHue=%23fcfbfb&clientId=u030831e2-9b97-4&from=paste&height=983&id=u8bef4757&originHeight=983&originWidth=2488&originalType=binary&ratio=1&rotation=0&showTitle=false&size=139537&status=done&style=none&taskId=u20e27a79-1aca-463b-a23b-c5f930d8caa&title=&width=2488)
2. Fill in the project name and other information.
The project name is a required field, cannot be the same as other projects, and cannot be changed after creating the project.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691486874906-01294dfe-e4bc-452b-9bd1-9a020832f615.png#averageHue=%239c9c9c&clientId=u030831e2-9b97-4&from=paste&height=1079&id=kWUOt&originHeight=1079&originWidth=2489&originalType=binary&ratio=1&rotation=0&showTitle=false&size=157435&status=done&style=none&taskId=u42caeda6-0d88-4e42-94d4-cecabbd8043&title=&width=2489)
3. Click "OK" to complete the project creation
#### 5. Upload converted  data

1. Select a project and click Upload File
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691486982066-763f945d-6f10-4796-aab7-6484731268ec.png#averageHue=%23fcfbfb&clientId=u8d4b4bef-cbd1-4&from=paste&height=963&id=vn3cc&originHeight=963&originWidth=2494&originalType=binary&ratio=1&rotation=0&showTitle=false&size=140218&status=done&style=none&taskId=u757b1529-003c-4cd9-99b0-6429455b569&title=&width=2494)


2. Click "New batch", enter the batch name in the pop-up input box, click "confirm" to complete the batch creation, and select the converted aird file in the pop-up new page and wait for the upload complete.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487040013-ac82cca7-0c8a-4f04-8048-d7b1ee4c0944.png#averageHue=%23cac9c9&clientId=u8d4b4bef-cbd1-4&from=paste&height=1158&id=U3y12&originHeight=1158&originWidth=2490&originalType=binary&ratio=1&rotation=0&showTitle=false&size=188908&status=done&style=none&taskId=u88ff66e4-359d-45f2-9ace-113d4609328&title=&width=2490)

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487192572-d6fd0537-fb42-446a-8c46-3f4a86f1f746.png#averageHue=%23fcfbfb&clientId=u8d4b4bef-cbd1-4&from=paste&height=273&id=uc082b409&originHeight=453&originWidth=1177&originalType=binary&ratio=1&rotation=0&showTitle=false&size=19851&status=done&style=none&taskId=u5a3d2c65-b620-48e4-a5be-b221c6ee0a2&title=&width=709)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487245144-e2566c7e-1672-445f-be56-a87f3898acdf.png#averageHue=%23fcfbfa&clientId=u8d4b4bef-cbd1-4&from=paste&height=596&id=u58f9ce8c&originHeight=957&originWidth=1141&originalType=binary&ratio=1&rotation=0&showTitle=false&size=80485&status=done&style=none&taskId=u162bf734-d70d-4487-8d3c-271b15c3406&title=&width=710)

3. Refresh the "Project Workbench" interface reload run count, click to view the run details

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487309395-71e4d5c1-0f27-45c7-ab15-2869ad57d490.png#averageHue=%23fcfbfb&clientId=u8d4b4bef-cbd1-4&from=paste&height=974&id=uc8afa4f3&originHeight=974&originWidth=2496&originalType=binary&ratio=1&rotation=0&showTitle=false&size=140140&status=done&style=none&taskId=ufbea93ba-2430-4c67-a448-82f71b6f3cf&title=&width=2496)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487332601-a9c7fb84-3be2-406a-b1c9-88c17f081a09.png#averageHue=%23fcfcfc&clientId=u8d4b4bef-cbd1-4&from=paste&height=1113&id=ude5db14b&originHeight=1113&originWidth=2470&originalType=binary&ratio=1&rotation=0&showTitle=false&size=126641&status=done&style=none&taskId=u98eb71b8-c161-49e7-909a-55f1f4ae536&title=&width=2470)
#### 6. View MS file contents

1. Click "Panel" on the "Project" page.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487358698-ad4bfe72-444e-4dc1-bff4-81041fc3e0d3.png#averageHue=%23fbfbfb&clientId=u8d4b4bef-cbd1-4&from=paste&height=1051&id=ua26f7b54&originHeight=1051&originWidth=2490&originalType=binary&ratio=1&rotation=0&showTitle=false&size=141526&status=done&style=none&taskId=uadea4287-f374-4510-9cf0-6a85b8a68b1&title=&width=2490)
2. View EICs in MS files

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487380626-16ec2b88-f185-4293-a3ea-447f8f9d1f62.png#averageHue=%23fcfcfc&clientId=u8d4b4bef-cbd1-4&from=paste&height=1147&id=ufd9f63ae&originHeight=1147&originWidth=2469&originalType=binary&ratio=1&rotation=0&showTitle=false&size=188178&status=done&style=none&taskId=u99522c62-7f1b-4735-bb29-106f025b7a0&title=&width=2469)

#### 7. Create an analysis method

1. Click "Method"

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487437703-9345fbbb-9ee8-4adf-99ba-38921f127207.png#averageHue=%23fcfbfb&clientId=u8d4b4bef-cbd1-4&from=paste&height=446&id=ue85bb56b&originHeight=446&originWidth=2491&originalType=binary&ratio=1&rotation=0&showTitle=false&size=44241&status=done&style=none&taskId=ueaae99fe-c90f-4028-b3d4-222ee3d8edc&title=&width=2491)

2. Enter a method name and click OK

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487460403-c96d97ac-c238-4791-a955-cff89260c67d.png#averageHue=%23a09f9e&clientId=u8d4b4bef-cbd1-4&from=paste&height=414&id=u47930bd0&originHeight=414&originWidth=2495&originalType=binary&ratio=1&rotation=0&showTitle=false&size=48041&status=done&style=none&taskId=u1363d415-384d-4d02-be93-97003b28d55&title=&width=2495)

3. Select a target sample

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487477909-c0db83e0-64d3-48c4-ab01-f7b99c1581c5.png#averageHue=%23fcfcfc&clientId=u8d4b4bef-cbd1-4&from=paste&height=1184&id=uedc005a1&originHeight=1184&originWidth=1780&originalType=binary&ratio=1&rotation=0&showTitle=false&size=135163&status=done&style=none&taskId=u7686f613-432d-4e1b-9b80-ed7c47b184b&title=&width=1780)

4. Set parameters & Save parameters for each fragment, users can adjust the rt and peak picking parameters on this page.

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487494835-a7bd2a2a-c6bf-48bb-94a8-6ddbe39f1601.png#averageHue=%23fbfbfb&clientId=u8d4b4bef-cbd1-4&from=paste&height=1190&id=u453ff7ee&originHeight=1190&originWidth=1796&originalType=binary&ratio=1&rotation=0&showTitle=false&size=159759&status=done&style=none&taskId=u630b1638-1fac-42c0-b7af-33cff28662f&title=&width=1796)


5. Peak picking parameters
![image.png](https://cdn.nlark.com/yuque/0/2023/png/240744/1676102490393-51e97d84-2026-4a97-8597-f5f1cda44526.png#averageHue=%23000000&clientId=u9d9a5f73-f4fd-4&from=paste&height=1213&id=ufc2dce96&originHeight=2426&originWidth=1786&originalType=binary&ratio=2&rotation=0&showTitle=false&size=637155&status=done&style=none&taskId=ua9492c04-c9e9-4a12-b05c-1f75876d94d&title=&width=893)
#### 8. Submit analysis task

1. Click "Analysis" on the "Project" page
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487582499-e7a183da-d459-401b-89b1-c075effd0eb6.png#averageHue=%23fbfbfb&clientId=u8d4b4bef-cbd1-4&from=paste&height=1046&id=u5e3cf342&originHeight=1046&originWidth=2491&originalType=binary&ratio=1&rotation=0&showTitle=false&size=144028&status=done&style=none&taskId=u3edcf678-133b-40e8-a36c-2f4ade5bf39&title=&width=2491)
2. Click "Edit" to start editing the platform parameters
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487638249-9ab97fb2-659e-4062-be5f-b97855d3549a.png#averageHue=%23fbfafa&clientId=u8d4b4bef-cbd1-4&from=paste&height=454&id=o4nAC&originHeight=454&originWidth=2490&originalType=binary&ratio=1&rotation=0&showTitle=false&size=39498&status=done&style=none&taskId=ub98d53e0-850f-4a20-8604-5f90a25cfb4&title=&width=2490)
Configure the sample type. By default, the system classifies samples based on the sample name

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487676245-9321d7c5-40bf-48f0-b5d4-40755baf05aa.png#averageHue=%23c3c3c3&clientId=u8d4b4bef-cbd1-4&from=paste&height=1233&id=u1a6e8449&originHeight=1233&originWidth=2488&originalType=binary&ratio=1&rotation=0&showTitle=false&size=118526&status=done&style=none&taskId=udc5cd4bb-6589-4dd7-b395-221b54f0ebd&title=&width=2488)

3. Click analysis

When you click Analyze, you can select the method created above for analysis. If the method is not created before, MRMPro will use default parameters. You can modify the method based on the analysis result.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487702229-d6e431f1-9152-450e-a4c4-0e6b386e96bd.png#averageHue=%23f6f6f6&clientId=u8d4b4bef-cbd1-4&from=paste&height=722&id=ua87bbf3d&originHeight=722&originWidth=2489&originalType=binary&ratio=1&rotation=0&showTitle=false&size=56979&status=done&style=none&taskId=u4b603b4b-3806-460f-88da-59acaf5ef06&title=&width=2489)

4. Click "Trace" to view the analysis progress

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691487720828-a9e0062f-dcc6-4386-b8a8-56300eede99a.png#averageHue=%23f8f8f8&clientId=u8d4b4bef-cbd1-4&from=paste&height=1268&id=Sb65W&originHeight=1268&originWidth=2466&originalType=binary&ratio=1&rotation=0&showTitle=false&size=151068&status=done&style=none&taskId=u4c94d9f9-d83d-48b0-88af-1ea5479fb57&title=&width=2466)

#### 9. Inspect analysis results

1. After clicking "Start analyze", wait about 10 seconds to jump to the result batch inspection page.
Or click “Check”to jump to the batch inspection page.

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691488026608-f2aef20d-0f83-4725-a3a4-6e5449bf65ce.png#averageHue=%23e4c397&clientId=u8d4b4bef-cbd1-4&from=paste&height=1285&id=u9ed668f1&originHeight=1285&originWidth=2490&originalType=binary&ratio=1&rotation=0&showTitle=false&size=475968&status=done&style=none&taskId=ud2aa1564-38ed-4a12-a722-ae3fa8c6877&title=&width=2490)

2. Manually check and adjust results in batch

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691488052149-d55549b1-bf9d-4501-99d0-03d9c3341004.png#averageHue=%23e8cea3&clientId=u8d4b4bef-cbd1-4&from=paste&height=1291&id=uf9496daa&originHeight=1291&originWidth=2499&originalType=binary&ratio=1&rotation=0&showTitle=false&size=464330&status=done&style=none&taskId=udad04c73-d486-48c4-b19b-721b6cbe54c&title=&width=2499)
**Keyboard operation**：
	⬆️⬇️：switch to the compound above / below
	⬅️➡️：switch to the compound in the page above / below at the same row
	a：select EICs of all runs
	s：select EICs of runs of "SAMPLE" type
	ctrl/command/shift：select multiple samples
	1，2，3：switch the manual review status of EICs
	Backspace：submit the manual review status of EICs and set compound review status to failed.
	Enter：submit the manual review status of EICs and set compound review status to succeed.
	Space：submit the manual review status of EICs, set compound review status to succeed, and switch to the next compound.
**Sample batch selection**：
	Click on matrix graph：single click，ctrl/shift + click
	Keyboard shortcut: a, s
	Draw a box in EIC_in_one graph：draw a box containing EIC signal in EIC_in_on graph, and click“➕”to add selected EICs to a new group
	Auto grouping：Click the "Auto grouping" button to separate EICs with different distributions to different groups.
**Batch manual integration**:
	Select multiple EICs. The selected EICs will be showed in the EIC_in_one graph. Draw a line on the EIC_in_one graph from integration start RT to end RT. Double click or click "Submit" to apply the integration to selected EICs.
**Change parameters**:
	Click the "Method" button to change the parameters. Users can choose to apply the new parameters to the compound in all samples or selected samples.

#### 10. Check quantification 

1. Direct quantification

step1: Click "Standard curve" to show the concentration graph.
step2: Fill in the concentrations of standard samples

![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691488165179-c4274931-6b21-44ce-a013-00b6798a0882.png#averageHue=%23e7cfa2&clientId=u8d4b4bef-cbd1-4&from=paste&height=1289&id=u11c6f801&originHeight=1289&originWidth=2491&originalType=binary&ratio=1&rotation=0&showTitle=false&size=459460&status=done&style=none&taskId=u1da9e58c-336b-4ba6-9920-51f7f9ec02e&title=&width=2491)

2. Relative quantification

a. Finish the manual check of internal standard compounds
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1687620002084-df4e71e4-c45d-48cb-b776-ee57a395ba58.png#averageHue=%23f4e1c2&clientId=u54bc8275-566e-4&from=paste&height=1283&id=ubeab5ef7&originHeight=1283&originWidth=2492&originalType=binary&ratio=1&rotation=0&showTitle=false&size=558547&status=done&style=none&taskId=u7d3bc93d-d03f-497e-9ad1-806a625455b&title=&width=2492)

b. Select a compound and enter its corresponding internal standard compound![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691488278521-420a2541-742f-44fc-9f28-2bcbd9bb64b1.png#averageHue=%23f4f4f3&clientId=u8d4b4bef-cbd1-4&from=paste&height=1287&id=uc220f634&originHeight=1287&originWidth=2490&originalType=binary&ratio=1&rotation=0&showTitle=false&size=367234&status=done&style=none&taskId=ub5dc0b4f-f398-4b52-b46e-05a6d430131&title=&width=2490)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691488405863-602b2648-00ca-450b-998f-8dd4ca7c3882.png#averageHue=%23f5eada&clientId=u8d4b4bef-cbd1-4&from=paste&height=1284&id=uaa1b4805&originHeight=1284&originWidth=2484&originalType=binary&ratio=1&rotation=0&showTitle=false&size=439947&status=done&style=none&taskId=uc67625f3-b037-48bd-b012-32cf813a77d&title=&width=2484)

c. Check the relative concentration curve
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22012470/1691488473961-4a594afe-2e8a-4edc-acb8-68bc71efc90c.png#averageHue=%23f5eada&clientId=u8d4b4bef-cbd1-4&from=paste&height=1233&id=u543d40e8&originHeight=1233&originWidth=2495&originalType=binary&ratio=1&rotation=0&showTitle=false&size=374232&status=done&style=none&taskId=u8ce09e24-4791-4089-b5f3-8d315cd3f4a&title=&width=2495)

#### 11. Download analysis report
Click “Export report”on the "Overview" page to download the report.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/240744/1691492476125-b8792cd0-bb43-4787-9ea0-252f6bec0dcd.png#averageHue=%23fbfafa&clientId=u7c7af861-1ef1-4&from=paste&height=334&id=u17ce5705&originHeight=501&originWidth=2554&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=73095&status=done&style=none&taskId=u3722d1b8-b14c-4e12-aa6a-4e65690229e&title=&width=1702.6666666666667)
### 

