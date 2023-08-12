#### || Shree Ganeshaya Namaha || || Har Har Mahadev || || Jai Hinglaj Mata ||


# Hindus in Pakistan

This repo contains data regarding Hindus in Pakistan - list of Hindu temples (WIP), a crowd-sourced dataset on forced religious conversion cases of young Hindu girls (especially in Sindh) etc. This repo is meant to provide base data for further analysis by researchers, scholars and interested parties.  
  
Please provide proper attribution and reference if you use these datasets.  

#### You can check the website [here](https://tinyurl.com/vindicindic) to know more about other projects that I am working on.
  
---  
  
### 1. DAAHIP-W (Dataset of Atrocities Against Hindus in Pakistan - Women)

<img src="assets/collage.jpg" width="400">

#### 1.1 About
A detailed dataset has been prepared for cases relating to abduction, violence, forced conversion of/on Hindu girls in 
Pakistan (especially Sindh that is home to ~94% Hindu population of Pakistan). The dataset has been primarily sourced 
from Twitter. While attempts have been made to capture data as accurately as possible, errors are regretted and any 
updates or additions to this dataset are welcome and appreciated.

#### 1.2 Initial Analyses
1. These attacks happen the most in areas with relatively high Hindu populations.

<img src="assets/heatmap.png" height="300"/>  <img src="assets/sindh_hindu_population_per_by_district.png" height="300"/>  

<i>Left: Heatmap of cases in the master dataset; right: Heatmap of Hindu population as a % of total population 
(source: <a href="https://github.com/vindicindic/pakistan_minorities">here</a>)</i> 

2. In most cases, the victims are dalits. The Pakistani census doesn't count dalits as Hindus. Perhaps, this is what keeps the problem of steady conversion under wraps.

#### 1.2 DAAHIP-W
This dataset called DAAHIP-W (Dataset of Atrocities Against Hindus in Pakistan - Women) contains 
a list of cases that capture critical details about recorded atrocities against Hindu women in Pakistan. You can access 
the dataset [here](data/daahip-w/20230131_list_violence_abductions_forced_conversions_hindu_women_in_pakistan.xlsx).

<table>
    <tr>
        <th>Current # cases in dataset</th>
        <td>116</td>
    </tr>
    <tr>
        <th>Time-horizon</th>
        <td>approx. Oct '22 - Aug '23</td>
    </tr>
</table>

**Data dictionary**: Click <a href="data/data_dictionary.xlsx">here</a> to access the data dictionary for this dataset 
(Sheet name = DAAHIP-W)  

**Additional data**: You can also check out photos of victims, perpetrators, FIR documents etc. in the `data` folder. 
Each case in the master dataset is indexed using a case ID. If there is any additional data for a case (e.g. pictures, 
documents etc.), you will find a dedicated folder for that case in the `data/daahip-w/forced_conversions_case_data` 
folder. For example, for case # 9, you will want to look at folder titled `case_9`.


#### 1.4 How can you help?

1. **Help me add new or missing cases to the dataset**

You can use <a href="https://docs.google.com/forms/d/e/1FAIpQLSfKJotL3I1i5zj-RV45OP-dm-J0CIopWCDQGisoZSkmKt4h7A/viewform">this Google Form</a> to inform me about any new/missing case. Thank you in advance!

2. **Help spread the word**

<img src="assets/poster_service.png" width="400">

I have developed a functionality to create customized posters for each case in the dataset. If you need a poster for any specific case, please write to me at vindicindic@gmail.com. 

#### 1.5 Credits and gratitude

Special thanks to the following people for sharing information on these cases:
1. [Narain Das Bheel](https://twitter.com/NarainDasBheel8)
2. [Anshul Saxena](https://twitter.com/AskAnshul)
3. Sakshi Singh


---  
### 2. List of Hindu temple sites in Pakistan
A list of 343 Hindu temple sites has been published. The temple names and location details have been sourced from the 
article [here](https://en.wikipedia.org/wiki/List_of_Hindu_temples_in_Pakistan). Many of these sites have been 
completely ruined, or worse, converted. The Pakistani government has taken very little efforts to protect these temples.
The list includes Hindu, Jain and Sikh religious sites. The temples locations have been geocoded. Currently, the dataset
is being improved by addition of additional attributes that help track the status of these sites. Any help with this 
work  is appreciated. 

The dataset can be accessed [here](data/list_hindu_temples_in_pak/20230408_list_hindu_temples_pakistan.xlsx).

----  
## Get involved

1. If you wish to save Pakistani Hindu girls from being abducted and forcibly converted, consider getting involved with Project Chingari. You can check the details [here](https://hindupact.org/category/chingari-project/).

2. To suggest any changes or additions to this dataset, please write to vindicindic@gmail.com

3. I am currently looking for volunteers who can read Urdu and help me extract data from images of documents. Please write to me at vindicindic@gmail.com if you'd like to help. 
