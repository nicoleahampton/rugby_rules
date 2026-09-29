# rugby_rules

```
rugby_rules/
├── data/
│   ├── rugby_test_matches_per_year_backfilled.csv
│   ├── rugby_laws_per_year.csv
│   ├── hierarchical_trees/
│   │   ├── final_scrum_branches/
│   │   ├── original/                  
│   │   └── flattened/                  
│   ├── interdependencies/
│   │   ├── laws/                  
│   │   └── laws_plan_defs/          
│   └── text_files/
|       ├── original_texts/                  
|       ├── cleaned_texts/                  
|       └── cleaned_relavent_texts/
└── notebooks/
    ├── clean_text_visualization.ipynb
    ├── heirarchical_trees_paragraphs.ipynb
    ├── hierarchical_tree_analysis.ipynb
    ├── interdependencies.ipynb                  
    ├── interdependencies_analysis.ipynb                 
    └── scrums.ipynb
```

```clean_text_visualization.ipynb``` = text-based statistics
```heirarchical_trees_paragraphs.ipynb``` = generates hierarchical rule trees
```hierarchical_tree_analysis.ipynb``` = hierarchical tree statistics
```interdependencies.ipynb``` = generates interdependency networks
```interdependencies_analysis.ipynb``` = interdependency network statistics
```scrums.ipynb``` = generates scrum trees and growth rates
