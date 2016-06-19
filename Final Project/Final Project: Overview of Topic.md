# Distribution of Rare Plants in Kentucky

**Persona/Scenario**

The Kentucky State Nature Preserves Commission (KSNPC) is pleased to announce an open proposal bidding for their Website Redesign and Development of their Kentucky Rare Plant Database. The Rare Plant Database provides information on rare plants across Kentucky, and it is utilized for different projects by private and public entities.  

The Kentucky State Nature Preserves Commission will provide all the data necessary for the development of this project.

**1. Why are we making this product?**

	1. To assist in the redesigning of KSNPC's Kentucky Rare Plant Database webpage.
    2. To capture the distribution of Kentucky rare plant species monitored in an interactive web map.
	3. To display the information on one page and in a user-friendly manner. 
    
**2. What do we want to get out of this product?**

    1. Showcase the rare plants in Kentucky and to create a standard for the Natural Heritage programs in North America.
	2. Display the Rare Plant Database and their distribution by species.
    3. Change the static map format to an interactive map format.
    
**3. What do our users want to get out of this product?**

    1. Knowledge of extant/historic distribution of rare plants by species.
    2. Visualize with a better design distribution of plants.
	3. Provide stakeholders and citizens information with potential as a planning/education/conservation tool.

**4. Content Requirements:**
	
	1. Data will be represented on a basemap creating a dot map.
    2. Data will be encoded as a polygon colored according to species occurences as observed and/or historic/extirpated.
	3. A legend will inform user of specific information regarding the selected species (name, family, ocurrence, etc).  
	4. An info window might also be available with more information regarding species habitat, description, phenology, etc.
	
**5. Functional Requirements:**

	1. Map will load data dynamically from a CSV and JSON file.
	2. One data layer will be created with the distribution of a selected species that either is observed and/or historic/extirpated.
	3. Data layer will be drawn to map.
	4. Additional information will be attached to each county polygon on a click or hover.
    5. Upon a click on a protected area polygon the map will automatically zoom in at least one level.
    6. A search box will be added to the map.
    
**Revision: Overview of Topic** 
   
   Rich Donohue
   
    I don't have a good sense of the data yet from your description. Are the data simply whether or not a species of plant exists within a county? Like presented here? http://eppcapp.ky.gov/nprareplants/search.aspx?county=Calloway
   
   Maria 
   
    Yes, the csv file contains a code for each species.  Each species can be distributed in one county or several counties. 
   
   Rich Donohue
  
    Are all data aggregated to the county level, or are there other polygons?
    
   Maria
    
    The data is aggregated to the county level. There are no other polygons. Initally I thought, we could show the exact point of distribution, but the plants can be target of trafficking and coordinates aren't available. 
    
   Rich Donohue
    
    Would the choropleth then be darker shades for more rare species within each county?
    
   Maria
    
    I wanted to make a choropleth just as a base or background for the map because I feel that my data is very simple with only one layer, but that isn't very helpful.  
    
   Rich Donohue
    
    Would your map allow the user to select the specific plant and then show which counties it exists in, like this? I think this is potentially more useful than the choropleth of total counts.
    
   Maria
   
    Yes, I agree.  That was my intention, but I didn't express my ideas well.  Nevertheless, I wanted to have a dropdown with the option of searching data by county. With that said, I am not sure how I am going to re-organized the data. I have the csv added to this file lab 06 for your review.  
   