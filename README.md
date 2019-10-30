# CS573-Final-Project

## Data

The data I used for my project comes from three sources:  National Association of Corporate Relations Officers [NACRO](https://nacrocon.org/) membership data;  NACRO member survey data;  [College Scorecard](https://collegescorecard.ed.gov/data/) data.  

## Visualizations

The project is composed of four visualizations:  a NACRO membership map, a map of corporate engagement of NACRO member institutions, an interactive bar chart showing NACRO member office types by enrollment category, and an interactive scatterplot showing corporate engagement in relation to institutional pricing and outcomes.  Each of the visualizations is described in further detail below.

### Membership Map

This map shows the location of the institutions where NACRO members are located and the number of members at those institutions.  This is a first step towards the development of an online tool that could be incorporated into the NACRO website for members to use for networking purposes.  Further work to realize this tool is described in more detail in the "Future Work" section below.

[![image](https://user-images.githubusercontent.com/54547762/67868095-caf36a80-fb01-11e9-8b07-d0c3e811eea1.png)](https://beta.vizhub.com/JCarpenter-WPI/2766fc02e0c64090a49dfaba9069d36d)

### Corporate Engagement Map

This map shows the level of corporate engagement of NACRO members' institutions.  The interest in developing this map was to explore whether there were obvious patterns of engagement by geography.  For example, we might expect high levels of corporate engagement in areas with concentrations of IT of biomedical industry.  However, it is difficult to discern any pattern, perhaps because of the limited number of institutions in the dataset.

[![image](https://user-images.githubusercontent.com/54547762/67874210-fe86c280-fb0a-11e9-9fda-b29c530481d2.png)](https://beta.vizhub.com/JCarpenter-WPI/74a1369f50654ecca306a82d266a540d)

### NACRO Membership by Office Type

This bar chart shows the breakdown of NACRO membership by office type where the individual member works within their institution.  In addition, users may explore how this changes for different levels of enrollment, which could be interesting to compare the organizational structure for different sizes of institutions.



### Corporate Engagement with Pricing and Outcomes

This scatterplot shows the relationship between the level of corporate engagement of NACRO members' institutions and institutional pricing and outcomes.  The interest in exploring this relationship is based on the hypothesis that pricing would be lower and outcomes would be better for those institutions with higher levels of corporate engagement.  In addition, by putting these two plots side by side, users can explore where specific institutions lie in both plots.  For example, it may be interesting to see where a high priced instutition lies on the outcomes plot and vice versa.

## Future Work

Additional work is needed on the Membership Map to make it fully functional.  The Membership Map is the part of the project that could really add value for NACRO, whose members have expressed a high level of interest in networking.  NACRO leadership is interested in this mapping tool.  Also, the NACRO Membership by Office Type chart could be extended.  Specifically, the envisioned future work involves the following:

Membership Map:
1.  Incorporate funcationality to link to member contact info by clicking on the institutions on the map.
2.  Filters could be added for enrollment, Carnegie classification and/or type of institution (public/private).
3.  Regions could be color coded, with functionality to click on the region and link to list of members in that region.
4.  Zooming functionality would allow better viewing in more "crowded" geographies.

NACRO Membership by Office Type:
1.  Additional dropdown menus could be added for Carnegie classification and type of institution (public/private).
