```python
!python -m pip install --upgrade ipykernel

```

    Requirement already satisfied: ipykernel in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (6.29.5)
    Requirement already satisfied: comm>=0.1.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (0.2.2)
    Requirement already satisfied: debugpy>=1.6.5 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (1.8.1)
    Requirement already satisfied: ipython>=7.23.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (8.25.0)
    Requirement already satisfied: jupyter-client>=6.1.12 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (8.6.2)
    Requirement already satisfied: jupyter-core!=5.0.*,>=4.12 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (5.7.2)
    Requirement already satisfied: matplotlib-inline>=0.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (0.1.7)
    Requirement already satisfied: nest-asyncio in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (1.6.0)
    Requirement already satisfied: packaging in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (24.1)
    Requirement already satisfied: psutil in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (5.9.8)
    Requirement already satisfied: pyzmq>=24 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (26.0.3)
    Requirement already satisfied: tornado>=6.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (6.4.1)
    Requirement already satisfied: traitlets>=5.4.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipykernel) (5.14.3)
    Requirement already satisfied: decorator in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipython>=7.23.1->ipykernel) (5.1.1)
    Requirement already satisfied: jedi>=0.16 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipython>=7.23.1->ipykernel) (0.19.1)
    Requirement already satisfied: prompt-toolkit<3.1.0,>=3.0.41 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipython>=7.23.1->ipykernel) (3.0.47)
    Requirement already satisfied: pygments>=2.4.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipython>=7.23.1->ipykernel) (2.18.0)
    Requirement already satisfied: stack-data in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipython>=7.23.1->ipykernel) (0.6.3)
    Requirement already satisfied: colorama in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from ipython>=7.23.1->ipykernel) (0.4.6)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jupyter-client>=6.1.12->ipykernel) (2.9.0.post0)
    Requirement already satisfied: platformdirs>=2.5 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jupyter-core!=5.0.*,>=4.12->ipykernel) (4.2.2)
    Requirement already satisfied: pywin32>=300 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jupyter-core!=5.0.*,>=4.12->ipykernel) (306)
    Requirement already satisfied: parso<0.9.0,>=0.8.3 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jedi>=0.16->ipython>=7.23.1->ipykernel) (0.8.4)
    Requirement already satisfied: wcwidth in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from prompt-toolkit<3.1.0,>=3.0.41->ipython>=7.23.1->ipykernel) (0.2.13)
    Requirement already satisfied: six>=1.5 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from python-dateutil>=2.8.2->jupyter-client>=6.1.12->ipykernel) (1.16.0)
    Requirement already satisfied: executing>=1.2.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from stack-data->ipython>=7.23.1->ipykernel) (2.0.1)
    Requirement already satisfied: asttokens>=2.1.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from stack-data->ipython>=7.23.1->ipykernel) (2.4.1)
    Requirement already satisfied: pure-eval in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from stack-data->ipython>=7.23.1->ipykernel) (0.2.2)



```python
!python -m pip install --upgrade pip


```

    Requirement already satisfied: pip in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (24.1.2)



```python
pip install pandas
```

    Requirement already satisfied: pandas in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (2.2.2)
    Requirement already satisfied: numpy>=1.26.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pandas) (1.26.4)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pandas) (2.9.0.post0)
    Requirement already satisfied: pytz>=2020.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pandas) (2024.1)
    Requirement already satisfied: tzdata>=2022.7 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pandas) (2024.1)
    Requirement already satisfied: six>=1.5 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from python-dateutil>=2.8.2->pandas) (1.16.0)
    Note: you may need to restart the kernel to use updated packages.



```python
pip install openpyxl
```

    Requirement already satisfied: openpyxl in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (3.1.3)
    Requirement already satisfied: et-xmlfile in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from openpyxl) (1.1.0)
    Note: you may need to restart the kernel to use updated packages.



```python
import pandas as pd
```


```python
# importing excel file 
df = pd.read_excel('Census_2011.xlsx')
```


```python
# renaming the column names for uniformity (as mentioned in the document)
df=df.rename(columns={'State name':'State/UT','District name':'District','Male_Literate':'Literate_Male','Female_Literate':'Literate_Female','Rural_Households':'Households_Rural','Urban_Households':'Households_Urban','Age_Group_0_29':'Young_and_Adult','Age_Group_30_49':'Middle_Aged','Age_Group_50':'Senior_Citizen','Age not stated':'Age_Not_Started'})
```


```python
#checking whether the column names are renamed or not.
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>District code</th>
      <th>State/UT</th>
      <th>District</th>
      <th>Population</th>
      <th>Male</th>
      <th>Female</th>
      <th>Literate</th>
      <th>Literate_Male</th>
      <th>Literate_Female</th>
      <th>SC</th>
      <th>...</th>
      <th>Power_Parity_Rs_90000_150000</th>
      <th>Power_Parity_Rs_45000_150000</th>
      <th>Power_Parity_Rs_150000_240000</th>
      <th>Power_Parity_Rs_240000_330000</th>
      <th>Power_Parity_Rs_150000_330000</th>
      <th>Power_Parity_Rs_330000_425000</th>
      <th>Power_Parity_Rs_425000_545000</th>
      <th>Power_Parity_Rs_330000_545000</th>
      <th>Power_Parity_Above_Rs_545000</th>
      <th>Total_Power_Parity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>JAMMU AND KASHMIR</td>
      <td>Kupwara</td>
      <td>870354.0</td>
      <td>474190.0</td>
      <td>396164.0</td>
      <td>439654.0</td>
      <td>282823.0</td>
      <td>156831.0</td>
      <td>1048.0</td>
      <td>...</td>
      <td>94.0</td>
      <td>588.0</td>
      <td>71.0</td>
      <td>101.0</td>
      <td>172.0</td>
      <td>74.0</td>
      <td>10.0</td>
      <td>84.0</td>
      <td>15.0</td>
      <td>1119.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>JAMMU AND KASHMIR</td>
      <td>Badgam</td>
      <td>753745.0</td>
      <td>NaN</td>
      <td>355704.0</td>
      <td>335649.0</td>
      <td>207741.0</td>
      <td>127908.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>126.0</td>
      <td>562.0</td>
      <td>72.0</td>
      <td>89.0</td>
      <td>161.0</td>
      <td>96.0</td>
      <td>28.0</td>
      <td>124.0</td>
      <td>18.0</td>
      <td>1066.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>JAMMU AND KASHMIR</td>
      <td>Leh(Ladakh)</td>
      <td>133487.0</td>
      <td>78971.0</td>
      <td>54516.0</td>
      <td>93770.0</td>
      <td>62834.0</td>
      <td>30936.0</td>
      <td>488.0</td>
      <td>...</td>
      <td>46.0</td>
      <td>122.0</td>
      <td>15.0</td>
      <td>22.0</td>
      <td>NaN</td>
      <td>20.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>17.0</td>
      <td>242.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>JAMMU AND KASHMIR</td>
      <td>Kargil</td>
      <td>140802.0</td>
      <td>NaN</td>
      <td>63017.0</td>
      <td>NaN</td>
      <td>56301.0</td>
      <td>29935.0</td>
      <td>18.0</td>
      <td>...</td>
      <td>27.0</td>
      <td>114.0</td>
      <td>12.0</td>
      <td>18.0</td>
      <td>30.0</td>
      <td>19.0</td>
      <td>3.0</td>
      <td>22.0</td>
      <td>7.0</td>
      <td>214.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>JAMMU AND KASHMIR</td>
      <td>Punch</td>
      <td>NaN</td>
      <td>251899.0</td>
      <td>224936.0</td>
      <td>261724.0</td>
      <td>163333.0</td>
      <td>98391.0</td>
      <td>556.0</td>
      <td>...</td>
      <td>78.0</td>
      <td>346.0</td>
      <td>35.0</td>
      <td>50.0</td>
      <td>85.0</td>
      <td>59.0</td>
      <td>8.0</td>
      <td>67.0</td>
      <td>12.0</td>
      <td>629.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>635</th>
      <td>636</td>
      <td>PONDICHERRY</td>
      <td>Mahe</td>
      <td>41816.0</td>
      <td>19143.0</td>
      <td>22673.0</td>
      <td>36470.0</td>
      <td>16610.0</td>
      <td>19860.0</td>
      <td>144.0</td>
      <td>...</td>
      <td>2316.0</td>
      <td>4309.0</td>
      <td>1370.0</td>
      <td>838.0</td>
      <td>2208.0</td>
      <td>576.0</td>
      <td>978.0</td>
      <td>1554.0</td>
      <td>1446.0</td>
      <td>10027.0</td>
    </tr>
    <tr>
      <th>636</th>
      <td>637</td>
      <td>PONDICHERRY</td>
      <td>Karaikal</td>
      <td>200222.0</td>
      <td>97809.0</td>
      <td>102413.0</td>
      <td>154916.0</td>
      <td>79903.0</td>
      <td>75013.0</td>
      <td>35348.0</td>
      <td>...</td>
      <td>1063.0</td>
      <td>2408.0</td>
      <td>665.0</td>
      <td>340.0</td>
      <td>1005.0</td>
      <td>246.0</td>
      <td>NaN</td>
      <td>729.0</td>
      <td>341.0</td>
      <td>4890.0</td>
    </tr>
    <tr>
      <th>637</th>
      <td>638</td>
      <td>ANDAMAN AND NICOBAR ISLANDS</td>
      <td>Nicobars</td>
      <td>36842.0</td>
      <td>20727.0</td>
      <td>NaN</td>
      <td>25332.0</td>
      <td>15397.0</td>
      <td>9935.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>134.0</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>638</th>
      <td>639</td>
      <td>ANDAMAN AND NICOBAR ISLANDS</td>
      <td>North  AND Middle Andaman</td>
      <td>105597.0</td>
      <td>54861.0</td>
      <td>50736.0</td>
      <td>78683.0</td>
      <td>43186.0</td>
      <td>35497.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>NaN</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>639</th>
      <td>640</td>
      <td>ANDAMAN AND NICOBAR ISLANDS</td>
      <td>South Andaman</td>
      <td>NaN</td>
      <td>127283.0</td>
      <td>110859.0</td>
      <td>190266.0</td>
      <td>105794.0</td>
      <td>84472.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>1371.0</td>
      <td>3020.0</td>
      <td>649.0</td>
      <td>368.0</td>
      <td>1017.0</td>
      <td>265.0</td>
      <td>497.0</td>
      <td>762.0</td>
      <td>376.0</td>
      <td>5782.0</td>
    </tr>
  </tbody>
</table>
<p>640 rows × 118 columns</p>
</div>




```python
df.info(verbose=True)

```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 640 entries, 0 to 639
    Data columns (total 118 columns):
     #    Column                                                                                                   Dtype  
    ---   ------                                                                                                   -----  
     0    District code                                                                                            int64  
     1    State/UT                                                                                                 object 
     2    District                                                                                                 object 
     3    Population                                                                                               float64
     4    Male                                                                                                     float64
     5    Female                                                                                                   float64
     6    Literate                                                                                                 float64
     7    Literate_Male                                                                                            float64
     8    Literate_Female                                                                                          float64
     9    SC                                                                                                       float64
     10   Male_SC                                                                                                  float64
     11   Female_SC                                                                                                float64
     12   ST                                                                                                       float64
     13   Male_ST                                                                                                  float64
     14   Female_ST                                                                                                float64
     15   Workers                                                                                                  float64
     16   Male_Workers                                                                                             float64
     17   Female_Workers                                                                                           float64
     18   Main_Workers                                                                                             float64
     19   Marginal_Workers                                                                                         float64
     20   Non_Workers                                                                                              float64
     21   Cultivator_Workers                                                                                       float64
     22   Agricultural_Workers                                                                                     float64
     23   Household_Workers                                                                                        float64
     24   Other_Workers                                                                                            float64
     25   Hindus                                                                                                   float64
     26   Muslims                                                                                                  float64
     27   Christians                                                                                               float64
     28   Sikhs                                                                                                    float64
     29   Buddhists                                                                                                float64
     30   Jains                                                                                                    float64
     31   Others_Religions                                                                                         float64
     32   Religion_Not_Stated                                                                                      float64
     33   LPG_or_PNG_Households                                                                                    float64
     34   Housholds_with_Electric_Lighting                                                                         float64
     35   Households_with_Internet                                                                                 float64
     36   Households_with_Computer                                                                                 float64
     37   Households_Rural                                                                                         float64
     38   Households_Urban                                                                                         float64
     39   Households                                                                                               float64
     40   Below_Primary_Education                                                                                  float64
     41   Primary_Education                                                                                        float64
     42   Middle_Education                                                                                         float64
     43   Secondary_Education                                                                                      float64
     44   Higher_Education                                                                                         float64
     45   Graduate_Education                                                                                       float64
     46   Other_Education                                                                                          float64
     47   Literate_Education                                                                                       float64
     48   Illiterate_Education                                                                                     float64
     49   Total_Education                                                                                          float64
     50   Young_and_Adult                                                                                          float64
     51   Middle_Aged                                                                                              float64
     52   Senior_Citizen                                                                                           float64
     53   Age_Not_Started                                                                                          float64
     54   Households_with_Bicycle                                                                                  float64
     55   Households_with_Car_Jeep_Van                                                                             float64
     56   Households_with_Radio_Transistor                                                                         float64
     57   Households_with_Scooter_Motorcycle_Moped                                                                 float64
     58   Households_with_Telephone_Mobile_Phone_Landline_only                                                     float64
     59   Households_with_Telephone_Mobile_Phone_Mobile_only                                                       float64
     60   Households_with_TV_Computer_Laptop_Telephone_mobile_phone_and_Scooter_Car                                float64
     61   Households_with_Television                                                                               float64
     62   Households_with_Telephone_Mobile_Phone                                                                   float64
     63   Households_with_Telephone_Mobile_Phone_Both                                                              float64
     64   Condition_of_occupied_census_houses_Dilapidated_Households                                               float64
     65   Households_with_separate_kitchen_Cooking_inside_house                                                    float64
     66   Having_bathing_facility_Total_Households                                                                 float64
     67   Having_latrine_facility_within_the_premises_Total_Households                                             float64
     68   Ownership_Owned_Households                                                                               float64
     69   Ownership_Rented_Households                                                                              float64
     70   Type_of_bathing_facility_Enclosure_without_roof_Households                                               float64
     71   Type_of_fuel_used_for_cooking_Any_other_Households                                                       float64
     72   Type_of_latrine_facility_Pit_latrine_Households                                                          float64
     73   Type_of_latrine_facility_Other_latrine_Households                                                        float64
     74   Type_of_latrine_facility_Night_soil_disposed_into_open_drain_Households                                  float64
     75   Type_of_latrine_facility_Flush_pour_flush_latrine_connected_to_other_system_Households                   float64
     76   Not_having_bathing_facility_within_the_premises_Total_Households                                         float64
     77   Not_having_latrine_facility_within_the_premises_Alternative_source_Open_Households                       float64
     78   Main_source_of_drinking_water_Un_covered_well_Households                                                 float64
     79   Main_source_of_drinking_water_Handpump_Tubewell_Borewell_Households                                      float64
     80   Main_source_of_drinking_water_Spring_Households                                                          float64
     81   Main_source_of_drinking_water_River_Canal_Households                                                     float64
     82   Main_source_of_drinking_water_Other_sources_Households                                                   float64
     83   Main_source_of_drinking_water_Other_sources_Spring_River_Canal_Tank_Pond_Lake_Other_sources__Households  float64
     84   Location_of_drinking_water_source_Near_the_premises_Households                                           float64
     85   Location_of_drinking_water_source_Within_the_premises_Households                                         float64
     86   Main_source_of_drinking_water_Tank_Pond_Lake_Households                                                  float64
     87   Main_source_of_drinking_water_Tapwater_Households                                                        float64
     88   Main_source_of_drinking_water_Tubewell_Borehole_Households                                               float64
     89   Household_size_1_person_Households                                                                       float64
     90   Household_size_2_persons_Households                                                                      float64
     91   Household_size_1_to_2_persons                                                                            float64
     92   Household_size_3_persons_Households                                                                      float64
     93   Household_size_3_to_5_persons_Households                                                                 float64
     94   Household_size_4_persons_Households                                                                      float64
     95   Household_size_5_persons_Households                                                                      float64
     96   Household_size_6_8_persons_Households                                                                    float64
     97   Household_size_9_persons_and_above_Households                                                            float64
     98   Location_of_drinking_water_source_Away_Households                                                        float64
     99   Married_couples_1_Households                                                                             float64
     100  Married_couples_2_Households                                                                             float64
     101  Married_couples_3_Households                                                                             float64
     102  Married_couples_3_or_more_Households                                                                     float64
     103  Married_couples_4_Households                                                                             float64
     104  Married_couples_5__Households                                                                            float64
     105  Married_couples_None_Households                                                                          float64
     106  Power_Parity_Less_than_Rs_45000                                                                          float64
     107  Power_Parity_Rs_45000_90000                                                                              float64
     108  Power_Parity_Rs_90000_150000                                                                             float64
     109  Power_Parity_Rs_45000_150000                                                                             float64
     110  Power_Parity_Rs_150000_240000                                                                            float64
     111  Power_Parity_Rs_240000_330000                                                                            float64
     112  Power_Parity_Rs_150000_330000                                                                            float64
     113  Power_Parity_Rs_330000_425000                                                                            float64
     114  Power_Parity_Rs_425000_545000                                                                            float64
     115  Power_Parity_Rs_330000_545000                                                                            float64
     116  Power_Parity_Above_Rs_545000                                                                             float64
     117  Total_Power_Parity                                                                                       float64
    dtypes: float64(115), int64(1), object(2)
    memory usage: 590.1+ KB



```python
# renaming State/UT column for uniformity
# converting all names into title case
df['State/UT'] = df['State/UT'].apply(str.title)
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>District code</th>
      <th>State/UT</th>
      <th>District</th>
      <th>Population</th>
      <th>Male</th>
      <th>Female</th>
      <th>Literate</th>
      <th>Literate_Male</th>
      <th>Literate_Female</th>
      <th>SC</th>
      <th>...</th>
      <th>Power_Parity_Rs_90000_150000</th>
      <th>Power_Parity_Rs_45000_150000</th>
      <th>Power_Parity_Rs_150000_240000</th>
      <th>Power_Parity_Rs_240000_330000</th>
      <th>Power_Parity_Rs_150000_330000</th>
      <th>Power_Parity_Rs_330000_425000</th>
      <th>Power_Parity_Rs_425000_545000</th>
      <th>Power_Parity_Rs_330000_545000</th>
      <th>Power_Parity_Above_Rs_545000</th>
      <th>Total_Power_Parity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Jammu And Kashmir</td>
      <td>Kupwara</td>
      <td>870354.0</td>
      <td>474190.0</td>
      <td>396164.0</td>
      <td>439654.0</td>
      <td>282823.0</td>
      <td>156831.0</td>
      <td>1048.0</td>
      <td>...</td>
      <td>94.0</td>
      <td>588.0</td>
      <td>71.0</td>
      <td>101.0</td>
      <td>172.0</td>
      <td>74.0</td>
      <td>10.0</td>
      <td>84.0</td>
      <td>15.0</td>
      <td>1119.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jammu And Kashmir</td>
      <td>Badgam</td>
      <td>753745.0</td>
      <td>NaN</td>
      <td>355704.0</td>
      <td>335649.0</td>
      <td>207741.0</td>
      <td>127908.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>126.0</td>
      <td>562.0</td>
      <td>72.0</td>
      <td>89.0</td>
      <td>161.0</td>
      <td>96.0</td>
      <td>28.0</td>
      <td>124.0</td>
      <td>18.0</td>
      <td>1066.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Jammu And Kashmir</td>
      <td>Leh(Ladakh)</td>
      <td>133487.0</td>
      <td>78971.0</td>
      <td>54516.0</td>
      <td>93770.0</td>
      <td>62834.0</td>
      <td>30936.0</td>
      <td>488.0</td>
      <td>...</td>
      <td>46.0</td>
      <td>122.0</td>
      <td>15.0</td>
      <td>22.0</td>
      <td>NaN</td>
      <td>20.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>17.0</td>
      <td>242.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Jammu And Kashmir</td>
      <td>Kargil</td>
      <td>140802.0</td>
      <td>NaN</td>
      <td>63017.0</td>
      <td>NaN</td>
      <td>56301.0</td>
      <td>29935.0</td>
      <td>18.0</td>
      <td>...</td>
      <td>27.0</td>
      <td>114.0</td>
      <td>12.0</td>
      <td>18.0</td>
      <td>30.0</td>
      <td>19.0</td>
      <td>3.0</td>
      <td>22.0</td>
      <td>7.0</td>
      <td>214.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Jammu And Kashmir</td>
      <td>Punch</td>
      <td>NaN</td>
      <td>251899.0</td>
      <td>224936.0</td>
      <td>261724.0</td>
      <td>163333.0</td>
      <td>98391.0</td>
      <td>556.0</td>
      <td>...</td>
      <td>78.0</td>
      <td>346.0</td>
      <td>35.0</td>
      <td>50.0</td>
      <td>85.0</td>
      <td>59.0</td>
      <td>8.0</td>
      <td>67.0</td>
      <td>12.0</td>
      <td>629.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>635</th>
      <td>636</td>
      <td>Pondicherry</td>
      <td>Mahe</td>
      <td>41816.0</td>
      <td>19143.0</td>
      <td>22673.0</td>
      <td>36470.0</td>
      <td>16610.0</td>
      <td>19860.0</td>
      <td>144.0</td>
      <td>...</td>
      <td>2316.0</td>
      <td>4309.0</td>
      <td>1370.0</td>
      <td>838.0</td>
      <td>2208.0</td>
      <td>576.0</td>
      <td>978.0</td>
      <td>1554.0</td>
      <td>1446.0</td>
      <td>10027.0</td>
    </tr>
    <tr>
      <th>636</th>
      <td>637</td>
      <td>Pondicherry</td>
      <td>Karaikal</td>
      <td>200222.0</td>
      <td>97809.0</td>
      <td>102413.0</td>
      <td>154916.0</td>
      <td>79903.0</td>
      <td>75013.0</td>
      <td>35348.0</td>
      <td>...</td>
      <td>1063.0</td>
      <td>2408.0</td>
      <td>665.0</td>
      <td>340.0</td>
      <td>1005.0</td>
      <td>246.0</td>
      <td>NaN</td>
      <td>729.0</td>
      <td>341.0</td>
      <td>4890.0</td>
    </tr>
    <tr>
      <th>637</th>
      <td>638</td>
      <td>Andaman And Nicobar Islands</td>
      <td>Nicobars</td>
      <td>36842.0</td>
      <td>20727.0</td>
      <td>NaN</td>
      <td>25332.0</td>
      <td>15397.0</td>
      <td>9935.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>134.0</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>638</th>
      <td>639</td>
      <td>Andaman And Nicobar Islands</td>
      <td>North  AND Middle Andaman</td>
      <td>105597.0</td>
      <td>54861.0</td>
      <td>50736.0</td>
      <td>78683.0</td>
      <td>43186.0</td>
      <td>35497.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>NaN</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>639</th>
      <td>640</td>
      <td>Andaman And Nicobar Islands</td>
      <td>South Andaman</td>
      <td>NaN</td>
      <td>127283.0</td>
      <td>110859.0</td>
      <td>190266.0</td>
      <td>105794.0</td>
      <td>84472.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>1371.0</td>
      <td>3020.0</td>
      <td>649.0</td>
      <td>368.0</td>
      <td>1017.0</td>
      <td>265.0</td>
      <td>497.0</td>
      <td>762.0</td>
      <td>376.0</td>
      <td>5782.0</td>
    </tr>
  </tbody>
</table>
<p>640 rows × 118 columns</p>
</div>




```python
# for special case starting letter of "and" should be small letter so replacing the values 
df.replace('Jammu And Kashmir','Jammu and Kashmir', inplace=True)
df.replace('Andaman And Nicobar Islands','Andaman and Nicobar Islands', inplace=True)
```


```python
df

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>District code</th>
      <th>State/UT</th>
      <th>District</th>
      <th>Population</th>
      <th>Male</th>
      <th>Female</th>
      <th>Literate</th>
      <th>Literate_Male</th>
      <th>Literate_Female</th>
      <th>SC</th>
      <th>...</th>
      <th>Power_Parity_Rs_90000_150000</th>
      <th>Power_Parity_Rs_45000_150000</th>
      <th>Power_Parity_Rs_150000_240000</th>
      <th>Power_Parity_Rs_240000_330000</th>
      <th>Power_Parity_Rs_150000_330000</th>
      <th>Power_Parity_Rs_330000_425000</th>
      <th>Power_Parity_Rs_425000_545000</th>
      <th>Power_Parity_Rs_330000_545000</th>
      <th>Power_Parity_Above_Rs_545000</th>
      <th>Total_Power_Parity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Jammu and Kashmir</td>
      <td>Kupwara</td>
      <td>870354.0</td>
      <td>474190.0</td>
      <td>396164.0</td>
      <td>439654.0</td>
      <td>282823.0</td>
      <td>156831.0</td>
      <td>1048.0</td>
      <td>...</td>
      <td>94.0</td>
      <td>588.0</td>
      <td>71.0</td>
      <td>101.0</td>
      <td>172.0</td>
      <td>74.0</td>
      <td>10.0</td>
      <td>84.0</td>
      <td>15.0</td>
      <td>1119.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jammu and Kashmir</td>
      <td>Badgam</td>
      <td>753745.0</td>
      <td>NaN</td>
      <td>355704.0</td>
      <td>335649.0</td>
      <td>207741.0</td>
      <td>127908.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>126.0</td>
      <td>562.0</td>
      <td>72.0</td>
      <td>89.0</td>
      <td>161.0</td>
      <td>96.0</td>
      <td>28.0</td>
      <td>124.0</td>
      <td>18.0</td>
      <td>1066.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Jammu and Kashmir</td>
      <td>Leh(Ladakh)</td>
      <td>133487.0</td>
      <td>78971.0</td>
      <td>54516.0</td>
      <td>93770.0</td>
      <td>62834.0</td>
      <td>30936.0</td>
      <td>488.0</td>
      <td>...</td>
      <td>46.0</td>
      <td>122.0</td>
      <td>15.0</td>
      <td>22.0</td>
      <td>NaN</td>
      <td>20.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>17.0</td>
      <td>242.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Jammu and Kashmir</td>
      <td>Kargil</td>
      <td>140802.0</td>
      <td>NaN</td>
      <td>63017.0</td>
      <td>NaN</td>
      <td>56301.0</td>
      <td>29935.0</td>
      <td>18.0</td>
      <td>...</td>
      <td>27.0</td>
      <td>114.0</td>
      <td>12.0</td>
      <td>18.0</td>
      <td>30.0</td>
      <td>19.0</td>
      <td>3.0</td>
      <td>22.0</td>
      <td>7.0</td>
      <td>214.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Jammu and Kashmir</td>
      <td>Punch</td>
      <td>NaN</td>
      <td>251899.0</td>
      <td>224936.0</td>
      <td>261724.0</td>
      <td>163333.0</td>
      <td>98391.0</td>
      <td>556.0</td>
      <td>...</td>
      <td>78.0</td>
      <td>346.0</td>
      <td>35.0</td>
      <td>50.0</td>
      <td>85.0</td>
      <td>59.0</td>
      <td>8.0</td>
      <td>67.0</td>
      <td>12.0</td>
      <td>629.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>635</th>
      <td>636</td>
      <td>Pondicherry</td>
      <td>Mahe</td>
      <td>41816.0</td>
      <td>19143.0</td>
      <td>22673.0</td>
      <td>36470.0</td>
      <td>16610.0</td>
      <td>19860.0</td>
      <td>144.0</td>
      <td>...</td>
      <td>2316.0</td>
      <td>4309.0</td>
      <td>1370.0</td>
      <td>838.0</td>
      <td>2208.0</td>
      <td>576.0</td>
      <td>978.0</td>
      <td>1554.0</td>
      <td>1446.0</td>
      <td>10027.0</td>
    </tr>
    <tr>
      <th>636</th>
      <td>637</td>
      <td>Pondicherry</td>
      <td>Karaikal</td>
      <td>200222.0</td>
      <td>97809.0</td>
      <td>102413.0</td>
      <td>154916.0</td>
      <td>79903.0</td>
      <td>75013.0</td>
      <td>35348.0</td>
      <td>...</td>
      <td>1063.0</td>
      <td>2408.0</td>
      <td>665.0</td>
      <td>340.0</td>
      <td>1005.0</td>
      <td>246.0</td>
      <td>NaN</td>
      <td>729.0</td>
      <td>341.0</td>
      <td>4890.0</td>
    </tr>
    <tr>
      <th>637</th>
      <td>638</td>
      <td>Andaman and Nicobar Islands</td>
      <td>Nicobars</td>
      <td>36842.0</td>
      <td>20727.0</td>
      <td>NaN</td>
      <td>25332.0</td>
      <td>15397.0</td>
      <td>9935.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>134.0</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>638</th>
      <td>639</td>
      <td>Andaman and Nicobar Islands</td>
      <td>North  AND Middle Andaman</td>
      <td>105597.0</td>
      <td>54861.0</td>
      <td>50736.0</td>
      <td>78683.0</td>
      <td>43186.0</td>
      <td>35497.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>NaN</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>639</th>
      <td>640</td>
      <td>Andaman and Nicobar Islands</td>
      <td>South Andaman</td>
      <td>NaN</td>
      <td>127283.0</td>
      <td>110859.0</td>
      <td>190266.0</td>
      <td>105794.0</td>
      <td>84472.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>1371.0</td>
      <td>3020.0</td>
      <td>649.0</td>
      <td>368.0</td>
      <td>1017.0</td>
      <td>265.0</td>
      <td>497.0</td>
      <td>762.0</td>
      <td>376.0</td>
      <td>5782.0</td>
    </tr>
  </tbody>
</table>
<p>640 rows × 118 columns</p>
</div>




```python
# Task 3
# Naming "state" for districts of telangana as "Telangana" 

telangana_districts = [
    'Adilabad', 'Nizamabad', 'Karimnagar', 'Medak', 'Hyderabad', 'Rangareddy', 'Mahbubnagar', 'Nalgonda', 'Warangal', 'Khammam'
]

df.loc[ df['District'].isin(telangana_districts), 'State/UT'] = 'Telangana'
```


```python
# Naming "state" for districts of "Ladakh" as "Ladakh" 

ladakh_districts = [
    'Leh(Ladakh)','Kargil'
]

df.loc[df['District'].isin(ladakh_districts), 'State/UT'] = 'Ladakh'

```


```python
# finding the amount of data missing
na_count = df.isna().sum()

na_df = na_count.reset_index()
na_df.columns = ['Column','Missing Values']

na_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Column</th>
      <th>Missing Values</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>District code</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>State/UT</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>District</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Population</td>
      <td>30</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Male</td>
      <td>30</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>113</th>
      <td>Power_Parity_Rs_330000_425000</td>
      <td>33</td>
    </tr>
    <tr>
      <th>114</th>
      <td>Power_Parity_Rs_425000_545000</td>
      <td>30</td>
    </tr>
    <tr>
      <th>115</th>
      <td>Power_Parity_Rs_330000_545000</td>
      <td>23</td>
    </tr>
    <tr>
      <th>116</th>
      <td>Power_Parity_Above_Rs_545000</td>
      <td>30</td>
    </tr>
    <tr>
      <th>117</th>
      <td>Total_Power_Parity</td>
      <td>32</td>
    </tr>
  </tbody>
</table>
<p>118 rows × 2 columns</p>
</div>




```python
# exporting the missing data and its values
na_df.to_excel('missing_values.xlsx', index=False)
```


```python
missing_percentage = df.isnull().mean() * 100
print(missing_percentage)
```

    District code                    0.00000
    State/UT                         0.00000
    District                         0.00000
    Population                       4.68750
    Male                             4.68750
                                      ...   
    Power_Parity_Rs_330000_425000    5.15625
    Power_Parity_Rs_425000_545000    4.68750
    Power_Parity_Rs_330000_545000    3.59375
    Power_Parity_Above_Rs_545000     4.68750
    Total_Power_Parity               5.00000
    Length: 118, dtype: float64



```python
df

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>District code</th>
      <th>State/UT</th>
      <th>District</th>
      <th>Population</th>
      <th>Male</th>
      <th>Female</th>
      <th>Literate</th>
      <th>Literate_Male</th>
      <th>Literate_Female</th>
      <th>SC</th>
      <th>...</th>
      <th>Power_Parity_Rs_90000_150000</th>
      <th>Power_Parity_Rs_45000_150000</th>
      <th>Power_Parity_Rs_150000_240000</th>
      <th>Power_Parity_Rs_240000_330000</th>
      <th>Power_Parity_Rs_150000_330000</th>
      <th>Power_Parity_Rs_330000_425000</th>
      <th>Power_Parity_Rs_425000_545000</th>
      <th>Power_Parity_Rs_330000_545000</th>
      <th>Power_Parity_Above_Rs_545000</th>
      <th>Total_Power_Parity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Jammu and Kashmir</td>
      <td>Kupwara</td>
      <td>870354.0</td>
      <td>474190.0</td>
      <td>396164.0</td>
      <td>439654.0</td>
      <td>282823.0</td>
      <td>156831.0</td>
      <td>1048.0</td>
      <td>...</td>
      <td>94.0</td>
      <td>588.0</td>
      <td>71.0</td>
      <td>101.0</td>
      <td>172.0</td>
      <td>74.0</td>
      <td>10.0</td>
      <td>84.0</td>
      <td>15.0</td>
      <td>1119.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jammu and Kashmir</td>
      <td>Badgam</td>
      <td>753745.0</td>
      <td>NaN</td>
      <td>355704.0</td>
      <td>335649.0</td>
      <td>207741.0</td>
      <td>127908.0</td>
      <td>NaN</td>
      <td>...</td>
      <td>126.0</td>
      <td>562.0</td>
      <td>72.0</td>
      <td>89.0</td>
      <td>161.0</td>
      <td>96.0</td>
      <td>28.0</td>
      <td>124.0</td>
      <td>18.0</td>
      <td>1066.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Ladakh</td>
      <td>Leh(Ladakh)</td>
      <td>133487.0</td>
      <td>78971.0</td>
      <td>54516.0</td>
      <td>93770.0</td>
      <td>62834.0</td>
      <td>30936.0</td>
      <td>488.0</td>
      <td>...</td>
      <td>46.0</td>
      <td>122.0</td>
      <td>15.0</td>
      <td>22.0</td>
      <td>NaN</td>
      <td>20.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>17.0</td>
      <td>242.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Ladakh</td>
      <td>Kargil</td>
      <td>140802.0</td>
      <td>NaN</td>
      <td>63017.0</td>
      <td>NaN</td>
      <td>56301.0</td>
      <td>29935.0</td>
      <td>18.0</td>
      <td>...</td>
      <td>27.0</td>
      <td>114.0</td>
      <td>12.0</td>
      <td>18.0</td>
      <td>30.0</td>
      <td>19.0</td>
      <td>3.0</td>
      <td>22.0</td>
      <td>7.0</td>
      <td>214.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Jammu and Kashmir</td>
      <td>Punch</td>
      <td>NaN</td>
      <td>251899.0</td>
      <td>224936.0</td>
      <td>261724.0</td>
      <td>163333.0</td>
      <td>98391.0</td>
      <td>556.0</td>
      <td>...</td>
      <td>78.0</td>
      <td>346.0</td>
      <td>35.0</td>
      <td>50.0</td>
      <td>85.0</td>
      <td>59.0</td>
      <td>8.0</td>
      <td>67.0</td>
      <td>12.0</td>
      <td>629.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>635</th>
      <td>636</td>
      <td>Pondicherry</td>
      <td>Mahe</td>
      <td>41816.0</td>
      <td>19143.0</td>
      <td>22673.0</td>
      <td>36470.0</td>
      <td>16610.0</td>
      <td>19860.0</td>
      <td>144.0</td>
      <td>...</td>
      <td>2316.0</td>
      <td>4309.0</td>
      <td>1370.0</td>
      <td>838.0</td>
      <td>2208.0</td>
      <td>576.0</td>
      <td>978.0</td>
      <td>1554.0</td>
      <td>1446.0</td>
      <td>10027.0</td>
    </tr>
    <tr>
      <th>636</th>
      <td>637</td>
      <td>Pondicherry</td>
      <td>Karaikal</td>
      <td>200222.0</td>
      <td>97809.0</td>
      <td>102413.0</td>
      <td>154916.0</td>
      <td>79903.0</td>
      <td>75013.0</td>
      <td>35348.0</td>
      <td>...</td>
      <td>1063.0</td>
      <td>2408.0</td>
      <td>665.0</td>
      <td>340.0</td>
      <td>1005.0</td>
      <td>246.0</td>
      <td>NaN</td>
      <td>729.0</td>
      <td>341.0</td>
      <td>4890.0</td>
    </tr>
    <tr>
      <th>637</th>
      <td>638</td>
      <td>Andaman and Nicobar Islands</td>
      <td>Nicobars</td>
      <td>36842.0</td>
      <td>20727.0</td>
      <td>NaN</td>
      <td>25332.0</td>
      <td>15397.0</td>
      <td>9935.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>134.0</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>638</th>
      <td>639</td>
      <td>Andaman and Nicobar Islands</td>
      <td>North  AND Middle Andaman</td>
      <td>105597.0</td>
      <td>54861.0</td>
      <td>50736.0</td>
      <td>78683.0</td>
      <td>43186.0</td>
      <td>35497.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>NaN</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>639</th>
      <td>640</td>
      <td>Andaman and Nicobar Islands</td>
      <td>South Andaman</td>
      <td>NaN</td>
      <td>127283.0</td>
      <td>110859.0</td>
      <td>190266.0</td>
      <td>105794.0</td>
      <td>84472.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>1371.0</td>
      <td>3020.0</td>
      <td>649.0</td>
      <td>368.0</td>
      <td>1017.0</td>
      <td>265.0</td>
      <td>497.0</td>
      <td>762.0</td>
      <td>376.0</td>
      <td>5782.0</td>
    </tr>
  </tbody>
</table>
<p>640 rows × 118 columns</p>
</div>




```python
df['Population']  = df['Population'].fillna(df['Male'] + df['Female'])
df['Population'] = df['Population'].fillna(df['Hindus'] + df['Muslims'] + df['Christians'] + df['Sikhs'] + df['Buddhists'] + df['Jains'] + df['Others_Religions'] + df['Religion_Not_Stated'])
df['Population'] = df['Population'].fillna(df['Workers'] + df['Non_Workers'])
df['Population'] = df['Population'].fillna(df['Young_and_Adult'] + df['Middle_Aged'] + df['Senior_Citizen'] + df['Age_Not_Started'])


df['Male'] = df['Male'].fillna(df['Population'] - df['Female'])
df['Female'] = df['Female'].fillna(df['Population'] - df['Male'])


df['SC']  = df['SC'].fillna(df['Male_SC'] + df['Female_SC'])
df['Male_SC']  = df['Male_SC'].fillna(df['SC'] - df['Female_SC'])
df['Female_SC']  = df['Female_SC'].fillna(df['SC'] + df['Male_SC'])

df['ST']  = df['ST'].fillna(df['Male_ST'] + df['Female_ST'])
df['Male_ST']  = df['Male_ST'].fillna(df['ST'] - df['Female_ST'])
df['Female_ST']  = df['Female_ST'].fillna(df['ST'] + df['Male_ST'])

df['Workers'] = df['Workers'].fillna(df['Male_Workers'] + df['Female_Workers'])
df['Workers'] = df['Workers'].fillna(df['Population'] - df['Non_Workers'])
df['Workers'] = df['Workers'].fillna(df['Cultivator_Workers'] + df['Agricultural_Workers'] + df['Household_Workers'] + df['Other_Workers'])

df['Male_Workers'] = df['Male_Workers'].fillna(df['Workers'] - df['Female_Workers'])
df['Female_Workers'] = df['Female_Workers'].fillna(df['Workers'] - df['Male_Workers'])

df['Non_Workers'] = df['Non_Workers'].fillna(df['Population'] - df['Workers'])
df['Main_Workers'] = df['Main_Workers'].fillna(df['Workers'] - df['Marginal_Workers'])
df['Marginal_Workers'] = df['Marginal_Workers'].fillna(df['Workers'] - df['Main_Workers'])

df['Cultivator_Workers'] = df['Cultivator_Workers'].fillna(df['Workers'] - df['Agricultural_Workers'] + df['Household_Workers'] + df['Other_Workers'])
df['Agricultural_Workers'] = df['Agricultural_Workers'].fillna(df['Workers'] - df['Cultivator_Workers'] + df['Household_Workers'] + df['Other_Workers'])
df['Household_Workers'] = df['Household_Workers'].fillna(df['Workers'] - df['Agricultural_Workers'] + df['Cultivator_Workers'] + df['Other_Workers'])
df['Other_Workers'] = df['Other_Workers'].fillna(df['Workers'] - df['Agricultural_Workers'] + df['Household_Workers'] + df['Cultivator_Workers'])

df['Literate'] = df['Literate'].fillna(df['Literate_Male'] + df['Literate_Female'])
df['Literate_Male'] = df['Literate_Male'].fillna(df['Literate'] - df['Literate_Female'])
df['Literate_Female'] = df['Literate_Female'].fillna(df['Literate'] - df['Literate_Male'])

df['Young_and_Adult'] = df['Young_and_Adult'].fillna(df['Population'] - df['Middle_Aged'] - df['Senior_Citizen'] - df['Age_Not_Started'])
df['Middle_Aged'] = df['Middle_Aged'].fillna(df['Population'] - df['Young_and_Adult'] - df['Senior_Citizen'] - df['Age_Not_Started'])
df['Senior_Citizen'] = df['Senior_Citizen'].fillna(df['Population'] - df['Young_and_Adult'] - df['Middle_Aged'] - df['Age_Not_Started'])
df['Age_Not_Started'] = df['Age_Not_Started'].fillna(df['Population'] - df['Young_and_Adult'] - df['Middle_Aged'] - df['Senior_Citizen'])

df['Households'] = df['Households'].fillna(df['Households_Rural'] + df['Households_Urban'])
df['Households_Rural'] = df['Households_Rural'].fillna(df['Households'] - df['Households_Urban'])
df['Households_Urban'] = df['Households_Urban'].fillna(df['Households'] - df['Households_Rural'])

df['Hindus'] = df['Hindus'].fillna(df['Population'] - df['Muslims'] + df['Christians'] + df['Sikhs'] + df['Buddhists'] + df['Jains'] + df['Others_Religions'] + df['Religion_Not_Stated'])
df['Muslims'] = df['Muslims'].fillna(df['Population'] - df['Hindus'] + df['Christians'] + df['Sikhs'] + df['Buddhists'] + df['Jains'] + df['Others_Religions'] + df['Religion_Not_Stated'])
df['Christians'] = df['Christians'].fillna(df['Population'] - df['Muslims'] + df['Hindus'] + df['Sikhs'] + df['Buddhists'] + df['Jains'] + df['Others_Religions'] + df['Religion_Not_Stated'])
df['Sikhs'] = df['Sikhs'].fillna(df['Population'] - df['Muslims'] + df['Christians'] + df['Hindus'] + df['Buddhists'] + df['Jains'] + df['Others_Religions'] + df['Religion_Not_Stated'])
df['Buddhists'] = df['Buddhists'].fillna(df['Population'] - df['Muslims'] + df['Christians'] + df['Sikhs'] + df['Hindus'] + df['Jains'] + df['Others_Religions'] + df['Religion_Not_Stated'])
df['Jains'] = df['Jains'].fillna(df['Population'] - df['Muslims'] + df['Christians'] + df['Sikhs'] + df['Buddhists'] + df['Hindus'] + df['Others_Religions'] + df['Religion_Not_Stated'])
df['Others_Religions'] = df['Others_Religions'].fillna(df['Population'] - df['Muslims'] + df['Christians'] + df['Sikhs'] + df['Buddhists'] + df['Jains'] + df['Hindus'] + df['Religion_Not_Stated'])
df['Religion_Not_Stated'] = df['Religion_Not_Stated'].fillna(df['Population'] - df['Muslims'] + df['Christians'] + df['Sikhs'] + df['Buddhists'] + df['Jains'] + df['Others_Religions'] + df['Hindus'])

df['Literate_Education'] = df['Literate_Education'].fillna(df['Below_Primary_Education'] + df['Primary_Education'] + df['Middle_Education'] + df['Secondary_Education'] + df['Higher_Education'] + df['Graduate_Education'] +df['Other_Education'])
df['Below_Primary_Education'] = df['Below_Primary_Education'].fillna(df['Literate_Education'] - df['Primary_Education'] + df['Middle_Education'] + df['Secondary_Education'] + df['Higher_Education'] + df['Graduate_Education'] +df['Other_Education'])
df['Primary_Education'] = df['Primary_Education'].fillna(df['Literate_Education'] - df['Below_Primary_Education'] + df['Middle_Education'] + df['Secondary_Education'] + df['Higher_Education'] + df['Graduate_Education'] +df['Other_Education'])
df['Middle_Education'] = df['Middle_Education'].fillna(df['Literate_Education'] - df['Below_Primary_Education'] + df['Primary_Education'] + df['Secondary_Education'] + df['Higher_Education'] + df['Graduate_Education'] +df['Other_Education'])
df['Secondary_Education'] = df['Secondary_Education'].fillna(df['Literate_Education'] - df['Below_Primary_Education'] + df['Primary_Education'] + df['Middle_Education'] + df['Higher_Education'] + df['Graduate_Education'] +df['Other_Education'])
df['Higher_Education'] = df['Higher_Education'].fillna(df['Literate_Education'] - df['Below_Primary_Education'] + df['Primary_Education'] + df['Middle_Education'] + df['Secondary_Education'] + df['Graduate_Education'] +df['Other_Education'])
df['Graduate_Education'] = df['Graduate_Education'].fillna(df['Literate_Education'] - df['Below_Primary_Education'] + df['Primary_Education'] + df['Middle_Education'] + df['Secondary_Education'] + df['Higher_Education'] +df['Other_Education'])
df['Other_Education'] = df['Other_Education'].fillna(df['Literate_Education'] - df['Below_Primary_Education'] + df['Primary_Education'] + df['Middle_Education'] + df['Secondary_Education'] + df['Higher_Education'] +df['Graduate_Education'])

df['Total_Education'] = df['Total_Education'].fillna(df['Literate_Education'] + df['Illiterate_Education'])
df['Literate_Education'] = df['Literate_Education'].fillna(df['Total_Education'] - df['Illiterate_Education'])
df['Illiterate_Education'] = df['Illiterate_Education'].fillna(df['Total_Education'] - df['Literate_Education'])

df['Total_Power_Parity'] = df['Total_Power_Parity'].fillna(df['Power_Parity_Less_than_Rs_45000'] + df['Power_Parity_Rs_45000_150000'] + df['Power_Parity_Rs_150000_330000'] + df['Power_Parity_Rs_330000_545000'] + df['Power_Parity_Above_Rs_545000'])
 
df['Power_Parity_Rs_45000_150000'] = df['Power_Parity_Rs_45000_150000'].fillna(df['Power_Parity_Rs_45000_90000'] + df['Power_Parity_Rs_90000_150000'])
df['Power_Parity_Rs_45000_90000'] = df['Power_Parity_Rs_45000_90000'].fillna(df['Power_Parity_Rs_45000_150000'] - df['Power_Parity_Rs_90000_150000'])
df['Power_Parity_Rs_90000_150000'] = df['Power_Parity_Rs_90000_150000'].fillna(df['Power_Parity_Rs_45000_150000'] - df['Power_Parity_Rs_45000_90000'])

df['Power_Parity_Rs_150000_330000'] = df['Power_Parity_Rs_150000_330000'].fillna(df['Power_Parity_Rs_150000_240000'] + df['Power_Parity_Rs_240000_330000'])
df['Power_Parity_Rs_150000_240000'] = df['Power_Parity_Rs_150000_240000'].fillna(df['Power_Parity_Rs_150000_330000'] - df['Power_Parity_Rs_240000_330000'])
df['Power_Parity_Rs_240000_330000'] = df['Power_Parity_Rs_240000_330000'].fillna(df['Power_Parity_Rs_150000_330000'] - df['Power_Parity_Rs_150000_240000'])

df['Power_Parity_Rs_330000_545000'] = df['Power_Parity_Rs_330000_545000'].fillna(df['Power_Parity_Rs_330000_425000'] + df['Power_Parity_Rs_425000_545000'])
df['Power_Parity_Rs_330000_425000'] = df['Power_Parity_Rs_330000_425000'].fillna(df['Power_Parity_Rs_330000_545000'] - df['Power_Parity_Rs_425000_545000'])
df['Power_Parity_Rs_425000_545000'] = df['Power_Parity_Rs_425000_545000'].fillna(df['Power_Parity_Rs_330000_545000'] + df['Power_Parity_Rs_330000_425000'])

df['Power_Parity_Above_Rs_545000'] = df['Power_Parity_Above_Rs_545000'].fillna(df['Total_Power_Parity'] - df['Power_Parity_Less_than_Rs_45000'] + df['Power_Parity_Rs_45000_150000'] + df['Power_Parity_Rs_150000_330000'] + df['Power_Parity_Rs_330000_545000'])
df['Power_Parity_Less_than_Rs_45000'] = df['Power_Parity_Less_than_Rs_45000'].fillna(df['Total_Power_Parity'] - df['Power_Parity_Rs_45000_150000'] + df['Power_Parity_Rs_150000_330000'] + df['Power_Parity_Rs_330000_545000'] + df['Power_Parity_Above_Rs_545000'])





```


```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>District code</th>
      <th>State/UT</th>
      <th>District</th>
      <th>Population</th>
      <th>Male</th>
      <th>Female</th>
      <th>Literate</th>
      <th>Literate_Male</th>
      <th>Literate_Female</th>
      <th>SC</th>
      <th>...</th>
      <th>Power_Parity_Rs_90000_150000</th>
      <th>Power_Parity_Rs_45000_150000</th>
      <th>Power_Parity_Rs_150000_240000</th>
      <th>Power_Parity_Rs_240000_330000</th>
      <th>Power_Parity_Rs_150000_330000</th>
      <th>Power_Parity_Rs_330000_425000</th>
      <th>Power_Parity_Rs_425000_545000</th>
      <th>Power_Parity_Rs_330000_545000</th>
      <th>Power_Parity_Above_Rs_545000</th>
      <th>Total_Power_Parity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Jammu and Kashmir</td>
      <td>Kupwara</td>
      <td>870354.0</td>
      <td>474190.0</td>
      <td>396164.0</td>
      <td>439654.0</td>
      <td>282823.0</td>
      <td>156831.0</td>
      <td>1048.0</td>
      <td>...</td>
      <td>94.0</td>
      <td>588.0</td>
      <td>71.0</td>
      <td>101.0</td>
      <td>172.0</td>
      <td>74.0</td>
      <td>10.0</td>
      <td>84.0</td>
      <td>15.0</td>
      <td>1119.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jammu and Kashmir</td>
      <td>Badgam</td>
      <td>753745.0</td>
      <td>398041.0</td>
      <td>355704.0</td>
      <td>335649.0</td>
      <td>207741.0</td>
      <td>127908.0</td>
      <td>368.0</td>
      <td>...</td>
      <td>126.0</td>
      <td>562.0</td>
      <td>72.0</td>
      <td>89.0</td>
      <td>161.0</td>
      <td>96.0</td>
      <td>28.0</td>
      <td>124.0</td>
      <td>18.0</td>
      <td>1066.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Ladakh</td>
      <td>Leh(Ladakh)</td>
      <td>133487.0</td>
      <td>78971.0</td>
      <td>54516.0</td>
      <td>93770.0</td>
      <td>62834.0</td>
      <td>30936.0</td>
      <td>488.0</td>
      <td>...</td>
      <td>46.0</td>
      <td>122.0</td>
      <td>15.0</td>
      <td>22.0</td>
      <td>37.0</td>
      <td>20.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>17.0</td>
      <td>242.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Ladakh</td>
      <td>Kargil</td>
      <td>140802.0</td>
      <td>77785.0</td>
      <td>63017.0</td>
      <td>86236.0</td>
      <td>56301.0</td>
      <td>29935.0</td>
      <td>18.0</td>
      <td>...</td>
      <td>27.0</td>
      <td>114.0</td>
      <td>12.0</td>
      <td>18.0</td>
      <td>30.0</td>
      <td>19.0</td>
      <td>3.0</td>
      <td>22.0</td>
      <td>7.0</td>
      <td>214.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Jammu and Kashmir</td>
      <td>Punch</td>
      <td>476835.0</td>
      <td>251899.0</td>
      <td>224936.0</td>
      <td>261724.0</td>
      <td>163333.0</td>
      <td>98391.0</td>
      <td>556.0</td>
      <td>...</td>
      <td>78.0</td>
      <td>346.0</td>
      <td>35.0</td>
      <td>50.0</td>
      <td>85.0</td>
      <td>59.0</td>
      <td>8.0</td>
      <td>67.0</td>
      <td>12.0</td>
      <td>629.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>635</th>
      <td>636</td>
      <td>Pondicherry</td>
      <td>Mahe</td>
      <td>41816.0</td>
      <td>19143.0</td>
      <td>22673.0</td>
      <td>36470.0</td>
      <td>16610.0</td>
      <td>19860.0</td>
      <td>144.0</td>
      <td>...</td>
      <td>2316.0</td>
      <td>4309.0</td>
      <td>1370.0</td>
      <td>838.0</td>
      <td>2208.0</td>
      <td>576.0</td>
      <td>978.0</td>
      <td>1554.0</td>
      <td>1446.0</td>
      <td>10027.0</td>
    </tr>
    <tr>
      <th>636</th>
      <td>637</td>
      <td>Pondicherry</td>
      <td>Karaikal</td>
      <td>200222.0</td>
      <td>97809.0</td>
      <td>102413.0</td>
      <td>154916.0</td>
      <td>79903.0</td>
      <td>75013.0</td>
      <td>35348.0</td>
      <td>...</td>
      <td>1063.0</td>
      <td>2408.0</td>
      <td>665.0</td>
      <td>340.0</td>
      <td>1005.0</td>
      <td>246.0</td>
      <td>975.0</td>
      <td>729.0</td>
      <td>341.0</td>
      <td>4890.0</td>
    </tr>
    <tr>
      <th>637</th>
      <td>638</td>
      <td>Andaman and Nicobar Islands</td>
      <td>Nicobars</td>
      <td>36842.0</td>
      <td>20727.0</td>
      <td>16115.0</td>
      <td>25332.0</td>
      <td>15397.0</td>
      <td>9935.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>134.0</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>638</th>
      <td>639</td>
      <td>Andaman and Nicobar Islands</td>
      <td>North  AND Middle Andaman</td>
      <td>105597.0</td>
      <td>54861.0</td>
      <td>50736.0</td>
      <td>78683.0</td>
      <td>43186.0</td>
      <td>35497.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>685.0</td>
      <td>1895.0</td>
      <td>212.0</td>
      <td>134.0</td>
      <td>346.0</td>
      <td>70.0</td>
      <td>120.0</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>3151.0</td>
    </tr>
    <tr>
      <th>639</th>
      <td>640</td>
      <td>Andaman and Nicobar Islands</td>
      <td>South Andaman</td>
      <td>238142.0</td>
      <td>127283.0</td>
      <td>110859.0</td>
      <td>190266.0</td>
      <td>105794.0</td>
      <td>84472.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>1371.0</td>
      <td>3020.0</td>
      <td>649.0</td>
      <td>368.0</td>
      <td>1017.0</td>
      <td>265.0</td>
      <td>497.0</td>
      <td>762.0</td>
      <td>376.0</td>
      <td>5782.0</td>
    </tr>
  </tbody>
</table>
<p>640 rows × 118 columns</p>
</div>




```python
na_count = df.isna().sum()

na_df = na_count.reset_index()
na_df.columns = ['Column','Missing Values']

na_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Column</th>
      <th>Missing Values</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>District code</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>State/UT</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>District</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Population</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Male</td>
      <td>0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>113</th>
      <td>Power_Parity_Rs_330000_425000</td>
      <td>3</td>
    </tr>
    <tr>
      <th>114</th>
      <td>Power_Parity_Rs_425000_545000</td>
      <td>3</td>
    </tr>
    <tr>
      <th>115</th>
      <td>Power_Parity_Rs_330000_545000</td>
      <td>4</td>
    </tr>
    <tr>
      <th>116</th>
      <td>Power_Parity_Above_Rs_545000</td>
      <td>4</td>
    </tr>
    <tr>
      <th>117</th>
      <td>Total_Power_Parity</td>
      <td>9</td>
    </tr>
  </tbody>
</table>
<p>118 rows × 2 columns</p>
</div>




```python
# exporting the missing data and its values
na_df.to_excel('missing_values6.xlsx', index=False)
```


```python
df.to_json('Census.json', orient='records', lines=True)
```


```python
missing_percentage = df.isnull().mean() * 100
print(missing_percentage)
```

    District code                    0.00000
    State/UT                         0.00000
    District                         0.00000
    Population                       0.00000
    Male                             0.00000
                                      ...   
    Power_Parity_Rs_330000_425000    0.46875
    Power_Parity_Rs_425000_545000    0.46875
    Power_Parity_Rs_330000_545000    0.62500
    Power_Parity_Above_Rs_545000     0.62500
    Total_Power_Parity               1.40625
    Length: 118, dtype: float64



```python
!pip install streamlit pandas pymongo sqlalchemy
!pip install mysqlclient
!pip install mysql-connector-python

```

    Requirement already satisfied: streamlit in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (1.36.0)
    Requirement already satisfied: pandas in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (2.2.2)
    Requirement already satisfied: pymongo in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (4.7.3)
    Requirement already satisfied: sqlalchemy in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (2.0.31)
    Requirement already satisfied: altair<6,>=4.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (5.3.0)
    Requirement already satisfied: blinker<2,>=1.0.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (1.8.2)
    Requirement already satisfied: cachetools<6,>=4.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (5.3.3)
    Requirement already satisfied: click<9,>=7.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (8.1.7)
    Requirement already satisfied: numpy<3,>=1.20 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (1.26.4)
    Requirement already satisfied: packaging<25,>=20 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (24.1)
    Requirement already satisfied: pillow<11,>=7.1.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (10.3.0)
    Requirement already satisfied: protobuf<6,>=3.20 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (5.27.2)
    Requirement already satisfied: pyarrow>=7.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (16.1.0)
    Requirement already satisfied: requests<3,>=2.27 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (2.32.3)
    Requirement already satisfied: rich<14,>=10.14.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (13.7.1)
    Requirement already satisfied: tenacity<9,>=8.1.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (8.4.2)
    Requirement already satisfied: toml<2,>=0.10.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (0.10.2)
    Requirement already satisfied: typing-extensions<5,>=4.3.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (4.12.2)
    Requirement already satisfied: gitpython!=3.1.19,<4,>=3.0.7 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (3.1.43)
    Requirement already satisfied: pydeck<1,>=0.8.0b4 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (0.9.1)
    Requirement already satisfied: tornado<7,>=6.0.3 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (6.4.1)
    Requirement already satisfied: watchdog<5,>=2.1.5 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from streamlit) (4.0.1)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pandas) (2.9.0.post0)
    Requirement already satisfied: pytz>=2020.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pandas) (2024.1)
    Requirement already satisfied: tzdata>=2022.7 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pandas) (2024.1)
    Requirement already satisfied: dnspython<3.0.0,>=1.16.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from pymongo) (2.6.1)
    Requirement already satisfied: greenlet!=0.4.17 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from sqlalchemy) (3.0.3)
    Requirement already satisfied: jinja2 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from altair<6,>=4.0->streamlit) (3.1.4)
    Requirement already satisfied: jsonschema>=3.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from altair<6,>=4.0->streamlit) (4.22.0)
    Requirement already satisfied: toolz in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from altair<6,>=4.0->streamlit) (0.12.1)
    Requirement already satisfied: colorama in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from click<9,>=7.0->streamlit) (0.4.6)
    Requirement already satisfied: gitdb<5,>=4.0.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from gitpython!=3.1.19,<4,>=3.0.7->streamlit) (4.0.11)
    Requirement already satisfied: six>=1.5 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from python-dateutil>=2.8.2->pandas) (1.16.0)
    Requirement already satisfied: charset-normalizer<4,>=2 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from requests<3,>=2.27->streamlit) (3.3.2)
    Requirement already satisfied: idna<4,>=2.5 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from requests<3,>=2.27->streamlit) (3.7)
    Requirement already satisfied: urllib3<3,>=1.21.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from requests<3,>=2.27->streamlit) (2.2.1)
    Requirement already satisfied: certifi>=2017.4.17 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from requests<3,>=2.27->streamlit) (2024.6.2)
    Requirement already satisfied: markdown-it-py>=2.2.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from rich<14,>=10.14.0->streamlit) (3.0.0)
    Requirement already satisfied: pygments<3.0.0,>=2.13.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from rich<14,>=10.14.0->streamlit) (2.18.0)
    Requirement already satisfied: smmap<6,>=3.0.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from gitdb<5,>=4.0.1->gitpython!=3.1.19,<4,>=3.0.7->streamlit) (5.0.1)
    Requirement already satisfied: MarkupSafe>=2.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jinja2->altair<6,>=4.0->streamlit) (2.1.5)
    Requirement already satisfied: attrs>=22.2.0 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jsonschema>=3.0->altair<6,>=4.0->streamlit) (23.2.0)
    Requirement already satisfied: jsonschema-specifications>=2023.03.6 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jsonschema>=3.0->altair<6,>=4.0->streamlit) (2023.12.1)
    Requirement already satisfied: referencing>=0.28.4 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jsonschema>=3.0->altair<6,>=4.0->streamlit) (0.35.1)
    Requirement already satisfied: rpds-py>=0.7.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from jsonschema>=3.0->altair<6,>=4.0->streamlit) (0.18.1)
    Requirement already satisfied: mdurl~=0.1 in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (from markdown-it-py>=2.2.0->rich<14,>=10.14.0->streamlit) (0.1.2)
    Requirement already satisfied: mysqlclient in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (2.2.4)
    Requirement already satisfied: mysql-connector-python in c:\users\gagan\appdata\local\programs\python\python312\lib\site-packages (9.0.0)



```python
import streamlit as st
import pandas as pd
import mysql.connector
from pymongo import MongoClient
from sqlalchemy import create_engine


```


```python
def get_connection():
    conn = mysql.connector.connect(
    host="localhost",
    user="root",
    password="423906#",
    database="census"
    )
    return conn

# Create a cursor object
#cursor = conn.cursor()
```


```python
from pymongo import MongoClient

# Connect to local MongoDB without authentication
client = MongoClient('mongodb://localhost:27017/')
db = client.Census  # Replace 'database_name' with your database name
collection = db.DATA  # Replace 'collection_name' with your collection name

```


```python
cursor = collection.find()
df1 = pd.DataFrame(list(cursor))

```


```python
df1.columns = [col[:60] for col in df1.columns]
```


```python
mysql_engine = create_engine('mysql://root:423906#@localhost:3306/census')
```


```python
df1_without_id = df1.drop(columns=['_id'])
df1_without_id.to_sql('project_me32', con=mysql_engine, index=False, if_exists='replace')


```




    640




```python
app_code = """
import mysql.connector
import pandas as pd
import streamlit as st

# Function to establish the database connection
def get_connection():
    return mysql.connector.connect(
        host="localhost",
        user="root",
        password="423906#",
        database="census"
    )

# Function to execute SQL query and display results
def execute_query(query, conn):
    df = pd.read_sql(query, conn)
    return df

# Streamlit UI
st.title('MySQL Data Analysis')

queries = {
    'Total population of each district': "SELECT District, SUM(Population) AS total_population FROM project_me32 GROUP BY District;",
    'Literate males and females in each district': "SELECT District, SUM(Literate_Male) AS total_literate_males, SUM(Literate_Female) AS total_literate_females FROM project_me32 GROUP BY District;",
    'Percentage of workers in each district': "SELECT District, (SUM(Male_Workers) + SUM(Female_Workers)) / SUM(Population) * 100 AS worker_percentage FROM project_me32 GROUP BY District;",
    'Households with access to LPG or PNG in each district': "SELECT District, SUM(LPG_or_PNG_Households) AS households_with_lpg_png FROM project_me32 GROUP BY District;",
    'Religious composition in each district': "SELECT District, SUM(Hindus) AS Hindus, SUM(Muslims) AS Muslims, SUM(Christians) AS Christians, SUM(Sikhs) AS Sikhs, SUM(Buddhists) AS Buddhists, SUM(Jains) AS Jains, SUM(Others_Religions) AS Others_Religions, SUM(Religion_Not_Stated) AS Religion_Not_Stated FROM project_me32 GROUP BY District;",
    'Households with internet access in each district': "SELECT District, SUM(Households_with_Internet) AS households_with_internet FROM project_me32 GROUP BY District;",
    'Educational attainment distribution in each district': "SELECT District, SUM(Below_Primary_Education) AS Below_Primary, SUM(Primary_Education) AS `Primary`, SUM(Middle_Education) AS Middle, SUM(Secondary_Education) AS Secondary, SUM(Higher_Education) AS Higher, SUM(Graduate_Education) AS Graduate, SUM(Other_Education) AS Other FROM project_me32 GROUP BY District;",
    'Households with access to various modes of transportation in each district': "SELECT District, SUM(Households_with_Bicycle) AS households_with_bicycle, SUM(Households_with_Car_Jeep_Van) AS households_with_car, SUM(Households_with_Radio_Transistor) AS households_with_radio, SUM(Households_with_Television) AS households_with_television FROM project_me32 GROUP BY District;",
    'Condition of occupied census houses in each district': "SELECT District, SUM(Condition_of_occupied_census_houses_Dilapidated_Households) AS dilapidated, SUM(Households_with_separate_kitchen_Cooking_inside_house) AS with_separate_kitchen, SUM(Having_bathing_facility_Total_Households) AS with_bathing_facility, SUM(Having_latrine_facility_within_the_premises_Total_Households) AS with_latrine_facility FROM project_me32 GROUP BY District;",
    'Household size distribution in each district': "SELECT District, SUM(Household_size_1_person_Households) AS size_1, SUM(Household_size_2_persons_Households) AS size_2, SUM(Household_size_3_persons_Households) AS size_3, SUM(Household_size_4_persons_Households) AS size_4, SUM(Household_size_5_persons_Households) AS size_5, SUM(Household_size_6_8_persons_Households) AS size_6_8, SUM(Household_size_9_persons_and_above_Households) AS size_9_plus FROM project_me32 GROUP BY District;",
    'Total number of households in each state': "SELECT `State/UT`, SUM(Households) AS total_households FROM project_me32 GROUP BY `State/UT`;",
    'Households with a latrine facility within the premises in each state': "SELECT `State/UT`, SUM(Having_latrine_facility_within_the_premises_Total_Households) AS households_with_latrine FROM project_me32 GROUP BY `State/UT`;",
    'Average household size in each state': "SELECT `State/UT`, AVG(Household_size_1_person_Households + Household_size_2_persons_Households + Household_size_3_persons_Households + Household_size_4_persons_Households + Household_size_5_persons_Households + Household_size_6_8_persons_Households + Household_size_9_persons_and_above_Households) AS average_household_size FROM project_me32 GROUP BY `State/UT`;",
    'Households owned versus rented in each state': "SELECT `State/UT`, SUM(Ownership_Owned_Households) AS owned_households, SUM(Ownership_Rented_Households) AS rented_households FROM project_me32 GROUP BY `State/UT`;",
    'Distribution of different types of latrine facilities in each state': "SELECT `State/UT`, SUM(Type_of_latrine_facility_Pit_latrine_Households) AS pit_latrine, SUM(Type_of_latrine_facility_Flush_pour_flush_latrine_connected_) AS flush_latrine, SUM(Type_of_latrine_facility_Other_latrine_Households) AS other_latrine FROM project_me32 GROUP BY `State/UT`;",
    'Households with access to drinking water sources near the premises in each state': "SELECT `State/UT`, SUM(Location_of_drinking_water_source_Near_the_premises_Househol) AS households_with_water_near FROM project_me32 GROUP BY `State/UT`;",
    'Average household income distribution in each state': "SELECT `State/UT`, SUM(Power_Parity_Less_than_Rs_45000) AS Less_than_Rs_45000, SUM(Power_Parity_Rs_45000_90000) AS Rs_45000_90000, SUM(Power_Parity_Rs_90000_150000) AS Rs_90000_150000, SUM(Power_Parity_Rs_150000_240000) AS Rs_150000_240000, SUM(Power_Parity_Rs_240000_330000) AS Rs_240000_330000, SUM(Power_Parity_Rs_330000_425000) AS Rs_330000_425000, SUM(Power_Parity_Rs_425000_545000) AS Rs_425000_545000, SUM(Power_Parity_Above_Rs_545000) AS Above_Rs_545000 FROM project_me32 GROUP BY `State/UT`;",
    'Percentage of married couples with different household sizes in each state': "SELECT `State/UT`, (SUM(Married_couples_1_Households) / SUM(Households)) * 100 AS married_couples_1, (SUM(Married_couples_2_Households) / SUM(Households)) * 100 AS married_couples_2, (SUM(Married_couples_3_Households) / SUM(Households)) * 100 AS married_couples_3, (SUM(Married_couples_4_Households) / SUM(Households)) * 100 AS married_couples_4, (SUM(Married_couples_5__Households) / SUM(Households)) * 100 AS married_couples_5 FROM project_me32 GROUP BY `State/UT`;",
    'Households below the poverty line in each state based on the power parity categories': "SELECT `State/UT`, SUM(Power_Parity_Less_than_Rs_45000) AS households_below_poverty_line FROM project_me32 GROUP BY `State/UT`;",
    'Overall literacy rate in each state': "SELECT `State/UT`, (SUM(Literate) / SUM(Population)) * 100 AS literacy_rate FROM project_me32 GROUP BY `State/UT`;"
}

query_selected = st.selectbox('Select Query', list(queries.keys()))

if query_selected:
    query = queries[query_selected]
    st.subheader(f'Results of {query_selected}')
    
    # Establish connection
    conn = get_connection()
    
    # Execute query and get DataFrame
    result_df = execute_query(query, conn)
    
    # Display results
    st.write(result_df)
    
    # Close the connection
    conn.close()
"""

with open('app.py', 'w') as f:
    f.write(app_code)

```


```python
import subprocess
import time
from IPython.display import IFrame

# Function to run Streamlit app
def run_streamlit():
    subprocess.Popen(["streamlit", "run", "app.py"])

# Run Streamlit app
run_streamlit()

# Allow time for the Streamlit server to start
time.sleep(10)  # Adjust the sleep time as needed

# Define the URL of your Streamlit app
public_url = 'http://localhost:8501'  # Replace with the appropriate port if different

# Display the Streamlit app in an iframe
display(IFrame(src=public_url, width=800, height=600))

```



<iframe
    width="800"
    height="600"
    src="http://localhost:8501"
    frameborder="0"
    allowfullscreen

></iframe>


