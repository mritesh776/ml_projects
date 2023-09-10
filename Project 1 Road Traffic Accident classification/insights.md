# Data Analytics
## Dataset Inspection
1. Number of Rows: 12316
2. Number of columns: 32

| Column                       |   Non-Null Count | Dtype   |
|:-----------------------------|-----------------:|:--------|
| Time                         |           12,316 | object  |
| Day_of_week                  |           12,316 | object  |
| Age_band_of_driver           |           12,316 | object  |
| Sex_of_driver                |           12,316 | object  |
| Educational_level            |           11,575 | object  |
| Vehicle_driver_relation      |           11,737 | object  |
| Driving_experience           |           11,487 | object  |
| Type_of_vehicle              |           11,366 | object  |
| Owner_of_vehicle             |           11,834 | object  |
| Service_year_of_vehicle      |            8,388 | object  |
| Defect_of_vehicle            |            7,889 | object  |
| Area_accident_occured        |           12,077 | object  |
| Lanes_or_Medians             |           11,931 | object  |
| Road_allignment              |           12,174 | object  |
| Types_of_Junction            |           11,429 | object  |
| Road_surface_type            |           12,144 | object  |
| Road_surface_conditions      |           12,316 | object  |
| Light_conditions             |           12,316 | object  |
| Weather_conditions           |           12,316 | object  |
| Type_of_collision            |           12,161 | object  |
| Number_of_vehicles_involved  |           12,316 | int64   |
| Number_of_casualties         |           12,316 | int64   |
| Vehicle_movement             |           12,008 | object  |
| Casualty_class               |           12,316 | object  |
| Sex_of_casualty              |           12,316 | object  |
| Age_band_of_casualty         |           12,316 | object  |
| Casualty_severity            |           12,316 | object  |
| Work_of_casuality            |            9,118 | object  |
| Fitness_of_casuality         |            9,681 | object  |
| Pedestrian_movement          |           12,316 | object  |
| Cause_of_accident            |           12,316 | object  |
| Accident_severity            |           12,316 | object  |

3. Type of column 
    1. Number of Numerical columns: 2
    ['Number_of_vehicles_involved', 'Number_of_casualties']

    2. Number of Categorical columns: 30
    ['Time', 'Day_of_week', 'Age_band_of_driver', 'Sex_of_driver', 'Educational_level', 'Vehicle_driver_relation', 'Driving_experience', 'Type_of_vehicle', 'Owner_of_vehicle', 'Service_year_of_vehicle', 'Defect_of_vehicle', 'Area_accident_occured', 'Lanes_or_Medians', 'Road_allignment', 'Types_of_Junction', 'Road_surface_type', 'Road_surface_conditions', 'Light_conditions', 'Weather_conditions', 'Type_of_collision', 'Vehicle_movement', 'Casualty_class', 'Sex_of_casualty', 'Age_band_of_casualty', 'Casualty_severity', 'Work_of_casuality', 'Fitness_of_casuality', 'Pedestrian_movement', 'Cause_of_accident', 'Accident_severity']

    3. No Datetime column in your dataframe.

    - Pre-processing step :**Time needs to be converted into datetime**

4. No duplicate Values present in the dataset.
5. Missing values in the dataset.

| Column name                | Missing Values | % of Total Values |
|----------------------------|----------------|--------------------|
| defect_of_vehicle          | 4427           | 35.9               |
| service_year_of_vehicle    | 3928           | 31.9               |
| work_of_casuality          | 3198           | 26.0               |
| fitness_of_casuality       | 2635           | 21.4               |
| type_of_vehicle            | 950            | 7.7                |
| types_of_junction          | 887            | 7.2                |
| driving_experience         | 829            | 6.7                |
| educational_level          | 741            | 6.0                |
| vehicle_driver_relation    | 579            | 4.7                |
| owner_of_vehicle           | 482            | 3.9                |
| lanes_or_medians           | 385            | 3.1                |
| vehicle_movement           | 308            | 2.5                |
| area_accident_occurred     | 239            | 1.9                |
| road_surface_type          | 172            | 1.4                |
| type_of_collision          | 155            | 1.3                |
| road_alignment             | 142            | 1.2                |

6. Unique values in dataset

| Column name                 | Unique Values |
|-----------------------------|--------------|
| Time                        | 1074         |
| Cause_of_accident           | 20           |
| Type_of_vehicle             | 17           |
| Area_accident_occurred      | 14           |
| Vehicle_movement            | 13           |
| Type_of_collision           | 10           |
| Pedestrian_movement         | 9            |
| Weather_conditions          | 9            |
| Road_alignment              | 9            |
| Types_of_Junction           | 8            |
| Number_of_casualties        | 8            |
| Work_of_casuality           | 7            |
| Lanes_or_Medians            | 7            |
| Day_of_week                 | 7            |
| Driving_experience          | 7            |
| Educational_level           | 7            |
| Service_year_of_vehicle     | 6            |
| Age_band_of_casualty        | 6            |
| Number_of_vehicles_involved | 6            |
| Fitness_of_casuality        | 5            |
| Road_surface_type           | 5            |
| Age_band_of_driver          | 5            |
| Casualty_severity           | 4            |
| Road_surface_conditions     | 4            |
| Casualty_class              | 4            |
| Light_conditions            | 4            |
| Owner_of_vehicle            | 4            |
| Vehicle_driver_relation     | 4            |
| Sex_of_casualty             | 3            |
| Defect_of_vehicle           | 3            |
| Sex_of_driver               | 3            |
| Accident_severity           | 3            |

7. Target Variable = Accident_severity

| Values           | Count  |
|------------------|--------|
| Slight Injury    | 10415  |
| Serious Injury   | 1743   |
| Fatal injury     | 158    |
