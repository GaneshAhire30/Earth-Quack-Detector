# Earth Quack Detector

## Overview
* Based on aspects of building location and construction, your goal is to predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal.
 

## Problem description
* We're trying to predict the ordinal variable damage_grade, which represents a level of damage to the building that was hit by the earthquake. There are 3 grades of the damage:
1. 1 represents low damage 
2.	2 represents a medium amount of damage 
3. 3 represents almost complete destruction 

## Features

* The dataset mainly consists of information on the buildings' structure and their legal ownership. Each row in the dataset represents a specific building in the region that was hit by Gorkha earthquake.
* There are 39 columns in this dataset, where the building_id column is a unique and random identifier. The remaining 38 features are described in the section below. 
* Categorical variables have been obfuscated random lowercase ascii characters. The appearance of the same character in distinct columns does not imply the same original value.

## Description
1. geo_level_1_id, geo_level_2_id, geo_level_3_id (type: int): geographic region in which building exists, from largest (level 1) to most specific sub-region (level 3). Possible values: level 1: 0-30, level 2: 0-1427, level 3: 0-12567. 
2. count_floors_pre_eq (type: int): number of floors in the building before the earthquake. 
3. age (type: int): age of the building in years. 
4. area_percentage (type: int): normalized area of the building footprint. 
5. height_percentage (type: int): normalized height of the building footprint. 
6.land_surface_condition (type: categorical): surface condition of the land where the building was built. Possible values: n, o, t. 
7. foundation_type (type: categorical): type of foundation used while building. Possible values: h, i, r, u, w. 
8. roof_type (type: categorical): type of roof used while building. Possible values: n, q, x. 
9. ground_floor_type (type: categorical): type of the ground floor. Possible values: f, m, v, x, z. 
10. other_floor_type (type: categorical): type of constructions used in higher than the ground floors (except of roof). Possible values: j, q, s, x. 
11. position (type: categorical): position of the building. Possible values: j, o, s, t. 
12. plan_configuration (type: categorical): building plan configuration. Possible values: a, c, d, f, m, n, o, q, s, u. 
13. has_superstructure_adobe_mud (type: binary): flag variable that indicates if the superstructure was made of Adobe/Mud. 
14. has_superstructure_mud_mortar_stone (type: binary): flag variable that indicates if the superstructure was made of Mud Mortar - Stone. 
15. has_superstructure_stone_flag (type: binary): flag variable that indicates if the superstructure was made of Stone. 
16. has_superstructure_cement_mortar_stone (type: binary): flag variable that indicates if the superstructure was made of Cement Mortar - Stone. 
17. has_superstructure_mud_mortar_brick (type: binary): flag variable that indicates if the superstructure was made of Mud Mortar - Brick. 
18. has_superstructure_cement_mortar_brick (type: binary): flag variable that indicates if the superstructure was made of Cement Mortar - Brick. 
19. has_superstructure_timber (type: binary): flag variable that indicates if the superstructure was made of Timber. 
20. has_superstructure_bamboo (type: binary): flag variable that indicates if the superstructure was made of Bamboo. 
21. has_superstructure_rc_non_engineered (type: binary): flag variable that indicates if the superstructure was made of non-engineered reinforced concrete. 
22. has_superstructure_rc_engineered (type: binary): flag variable that indicates if the superstructure was made of engineered reinforced concrete. 
23. has_superstructure_other (type: binary): flag variable that indicates if the superstructure was made of any other material. 
24.	legal_ownership_status (type: categorical): legal ownership status of the land where building was built. Possible values: a, r, v, w. 
25. count_families (type: int): number of families that live in the building. 
26. has_secondary_use (type: binary): flag variable that indicates if the building was used for any secondary purpose. 
27. has_secondary_use_agriculture (type: binary): flag variable that indicates if the building was used for agricultural purposes. 
28. has_secondary_use_hotel (type: binary): flag variable that indicates if the building was used as a hotel. 
29. has_secondary_use_rental (type: binary): flag variable that indicates if the building was used for rental purposes. 
30. has_secondary_use_institution (type: binary): flag variable that indicates if the building was used as a location of any institution. 
31. has_secondary_use_school (type: binary): flag variable that indicates if the building was used as a school. 
32. has_secondary_use_industry (type: binary): flag variable that indicates if the building was used for industrial purposes. 
33. has_secondary_use_health_post (type: binary): flag variable that indicates if the building was used as a health post. 
34. has_secondary_use_gov_office (type: binary): flag variable that indicates if the building was used fas a government office. 
35. has_secondary_use_use_police (type: binary): flag variable that indicates if the building was used as a police station. 
36. has_secondary_use_other (type: binary): flag variable that indicates if the building was secondarily used for other purposes. 
 

