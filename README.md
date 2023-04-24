# master-recommendation-system
Master Recommendation System

## ✅ Setup Env
- Create Python environment\
`conda create -n env_name python=3.10`\
`conda activate env_name`
- Create Python environment\
`pip install -r .\path_to_requirements\requirements.txt`

## Recommendation systems
- Types of recommendation systems
  - Content-based recommendation engines: Suggest items similar to those in which the user has preceding shown interest
    - Finding similarities between unstructured documents:
      - Term Document Matrix (TDM)
      - Frequency count
      - TF-IDF
    - Using co-occurrence matrix
  - Collaborative filtering engines: Based on users having similar interests
  - Hybrid recommendation engines
- Limitations
  - The cold start problem
  - Metadata requirements
  - The data sparsity problem
  - Bias due to social influence
  - Limited data
- Practical applications
  - Two-thirds of the movies on Netflix are recommended.  
  - Thirty-five percent of Amazon's sales come from recommendations. 
  - On Google News, recommendations generate 38 percent more click-through. 
  - Attempts to predict a user's preference for an item is based on past ratings of other items. 
  - They can suggest courses to university students based on their needs and preferences. 
  - They can match resumes to jobs on online job portals.