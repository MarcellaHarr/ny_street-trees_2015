# New York 2015 Street Trees Census

![Photo by <a href="https://unsplash.com/photos/ObhUk9MP5-g?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink">Karen Uppal</a> on <a href="https://unsplash.com/@karenuppal?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>](src/img/karen-uppal-ObhUk9MP5-g-unsplash.jpg)
  
<br />

## [Introduction](#introduction)

## [Data Exploration](#data-exploration)

## [Data Visualization](#data-visualization)

## [Data Analysis](#data-analysis)

## [Conclusion](#conclusion)

<br />

<!-- toc -->

# Introduction

I recently came across this project through a YouTuber, Mısra Turp, and was inspired to expound upon the project using my own skills. I am conducting an Exploratory Data Analysis (EDA) on a dataset collected by the NYC Parks & Recreation and partner organizations. The dataset consists of tree species, diameter, and perception of health of trees organized by staff and volunteers. My goal is to understand the distribution of tree species, diameter, and health perception across New York City. Through this EDA, I hope to gain insights that can be used to guide decision-making and improve the management of trees in the city. I would like to thank Mısra Turp for providing me with this project.

<br />

# Data Exploration

I successfully stored and secured the street tree data from TreeCount! which is owned by NYC Open Data. The data was created and made available to the public on June 3, 2016 and was last updated on October 4, 2017. The data consists of 684K rows, 45 columns, and each row is a detailed record of a tree. The feature columns explored are:

| Column       | Description   | Type   | Relabeled |
| ------------- |:-------------:|:-----:|     -----:|
| tree_id      | Unique identification number for each tree point | Integer | **Tree_Id** |
| tree_dbh      | Tree diameter, ≈ 54in / 137cm above the ground | Float | **Tree_Dbh_in** |
| stump_diam    | Stump diameter rounded to the nearest (inch) | Float | **Stump_Diam_in** |
| curb_loc      | Location of tree bed in relationship to the curb | String | **Curb_Loc** |
| status    | Indicates whether the tree is alive, standing dead, or a stump | String  | **Status** |
| health        | Indicates the user's perception of tree health | String | **Health** |
| created_at    | Date when records were done | String | **Created_At** |
| spc_latin     | Scientific name for species, e.g. "Acer rubrum" | String | **Spc_Latin** |
| steward       | Unique signs of stewardship observed | String | **Steward** |
| sidewalk       | Indicates flags adjacent to if tree was damaged, cracked, or lifted | Integer | **Sidewalk** |
| problems  | Indicate tree problems | String  | **Problems** |
| root_stone | Root problem caused by paving stones in tree bed | Boolean | **Root_Stone** |
| root_grate | Root problem caused by metal grates in tree bed | Boolean | **Root_Grate** |
| root_other    | Indicates the presence of other root problems | Boolean | **Root_Other** |
| trunk_wire    | Trunk problem caused by wires or rope encircling the trunk | Boolean | **Trunk_Wire** |
| trnk_light    | Trunk problem caused by lighting installed on the tree | Boolean | **Trnk_Light** |
| trnk_other | Indicates the presence of other trunk problems | Boolean | **Trnk_Other** |
| brch_light    | Branch problem caused by lights (usually string lights) or wires | Boolean | **Brch_Light** |
| brch_shoe    | Branch problem caused by sneakers in the branches | Boolean | **Brch_Shoe** |
| brch_other    | Indicates the presence of other branch problems | Boolean | **Brch_Other** |


<br />
<br />

# Data Visualization

<div class="image-1">
  <img src="src/img/Tree_and_Stump_Overview_Plot.png" alt="Image 1" width="950" height="450">
</div>


<div class="image-2">
  <img src="src/img/Alive_Tree_Diameter_By_Health-Status_Conditions.png" alt="Image 2" width="475" height="225">
</div>
<div class="image-3">
  <img src="src/img/Stump_Diameter_By_Health-Status_Conditions.png" alt="Image 3" width="475" height="225">
</div>

<br />

<div class="image-4"><img src="src/img/Tree-Stump_Problems.png" width="950" height="450" alt="Image 4"></div>


<br />

<div class="image-5"><img src="src/img/Species_Scientific_Names_By_Conditions.png" width="950" height="450" alt="Image 5"></div>

<br />

<div class="image-6">
  <img src="src/img/Tree_Diameter_Distribution_without_Binwidth_and_Filtered.png" alt="Image 6" width="475" height="225">
</div>
<div class="image-7">
  <img src="src/img/Stump_Diameter_Distribution_without_Binwidth_and_Filtered.png" alt="Image 7" width="475" height="225">
</div>

<br />
<br />

# Data Analysis

Ut et velit in velit finibus posuere. Donec vel velit velit. Curabitur vel vestibulum velit, a consectetur eros. Donec est leo, varius quis mi vel, cursus cursus neque. Vivamus in elit sagittis, luctus eros eget, pulvinar ipsum.

```
<code here>
```

# Conclusion

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sed libero vel nisi lobortis rhoncus. Fusce at ullamcorper risus. 

- Phasellus vel velit vel velit tempus rhoncus vel vel velit. Donec et est rhoncus, vulputate velit ut, porta neque. 
- Donec vitae augue ut mi ultricies condimentum. 
- Duis volutpat bibendum pretium. Integer sollicitudin elementum dui, ac sodales ex aliquet sed. 
- Nulla gravida blandit augue, sed scelerisque nibh congue ut. 

Maecenas non quam at augue pretium dapibus. Praesent pellentesque, augue et commodo ultricies, mauris ante volutpat metus, sed tristique sapien ipsum eget odio. Mauris a condimentum orci, vel consequat odio. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turp

<style>
  .image-1{
    float: center;
    width: 100%;
    margin: 0;
    padding: 0;
  }
  .image-2{
    float: left;
    width: 50%;
    margin: 0;
    padding: 0;
  }
  .image-3{
    float: right;
    width: 50%;
    margin: 0;
    padding: 0;
  }
  .image-4{
    float: center;
    width: 100%;
    margin: 0;
    padding: 0;
  }
  .image-5{
    float: center;
    width: 100%;
    margin: 0;
    padding: 0;
  }
  .image-6{
    float: left;
    width: 50%;
    margin: 0;
    padding: 0;
  }
  .image-7{
    float: right;
    width: 50%;
    margin: 0;
    padding: 0;
  }
  img{
    width: 100%;
    height: auto;
  }
</style>