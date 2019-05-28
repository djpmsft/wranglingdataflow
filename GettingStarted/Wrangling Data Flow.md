Wrangling Data Flow-Getting Started
-----------------------------------

You can create a Wrangling Data Flow in Azure Data Factory in 2 ways:

1.  Click ‘+’ -\> ‘New Data Flow’ in Resource Explorer OR

![](media/a3133084ccbf838f479914fa281948b7.png)

![](media/7fcdeb0d75a94c913962c8710631fd5e.png)

Drag a ‘Data Flow (Preview)’ activity on authoring canvas and select ‘Wrangling
Data Flow’

![](media/30aef5e624830254573023dc9b811dd4.png)

1.  Add ‘Source’ Dataset(s) for Wrangling Data Flow. You can choose an existing
    dataset as source dataset or add a new source dataset. Also, choose a ‘Sink’
    Dataset. You can choose 1 or more source datasets but only 1 sink is allowed
    at this time. Choosing a ‘Sink’ dataset is optional. But you have to choose
    atleast 1 ‘source’ dataset.

![](media/6b0b1154c65c9565b58952f8af56e091.png)

>   **Note**: Only ADLS Gen 2 Delimited Text are supported for limited preview.

![](media/bf4ceafb57781dc3c2219391a7260d4f.png)

1.  Click ‘Create’ to open the Power Query Online mashup editor and you are
    ready to do code-free data preparation/wrangling.

![](media/a2d2f300d3039eeb4777ad071f4fb1c4.png)

1.  Click ‘Debug’ to debug a wrangling data flow activity in a pipeline or click
    ‘trigger now’ to do an on-demand run of last published pipeline

![](media/71c56ab34bca16aedd5862c0baffbd99.png)

1.  Click ‘Monitor’ tab to visualize the output of the triggered wrangling data
    flow activity run

![](media/425f9f03e8a8e07cbafc6647a152f55d.png)
