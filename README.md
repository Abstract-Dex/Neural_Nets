# Neural_Nets

Projects based on Artificial Neural Networks

## Project 1: Classification of Breast Cancer Data using Neural Networks

### Description

UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

<table border="1" class="dataframe">

<thead>

<tr style="text-align: right;">

<th></th>

<th>Features</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<th>0</th>

<td>ID</td>

<td>ID number</td>

</tr>

<tr>

<th>1</th>

<td>Diagnosis</td>

<td>Diagnosis (M = malignant, B = benign)</td>

</tr>

<tr>

<th>2</th>

<td>radius</td>

<td>Mean of distances from the center to points on the perimeter</td>

</tr>

<tr>

<th>3</th>

<td>texture</td>

<td>Standard deviation of gray-scale values</td>

</tr>

<tr>

<th>4</th>

<td>perimeter</td>

<td>Perimeter</td>

</tr>

<tr>

<th>5</th>

<td>area</td>

<td>Area</td>

</tr>

<tr>

<th>6</th>

<td>smoothness</td>

<td>Local variation in radius lengths</td>

</tr>

<tr>

<th>7</th>

<td>compactness</td>

<td>(Perimeter^2 / Area) - 1.0</td>

</tr>

<tr>

<th>8</th>

<td>concavity</td>

<td>Severity of concave portions of the contour</td>

</tr>

<tr>

<th>9</th>

<td>concave_points</td>

<td>Number of concave portions of the contour</td>

</tr>

<tr>

<th>10</th>

<td>symmetry</td>

<td>Symmetry</td>

</tr>

<tr>

<th>11</th>

<td>fractal_dimension</td>

<td>"Coastline approximation" - 1</td>

</tr>

</tbody>

</table>

Class distribution: 357 benign, 212 malignant

## Project 2: House Price Prediction using Neural Networks

### Description

Data from Kaggle:

https://www.kaggle.com/harlfoxem/housesalesprediction

#### Feature Columns

<table border="1" class="dataframe">

<thead>

<tr style="text-align: right;">

<th></th>

<th>Features</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<th>0</th>

<td>id</td>

<td>Unique ID for each home sold</td>

</tr>

<tr>

<th>1</th>

<td>date</td>

<td>Date of the home sale</td>

</tr>

<tr>

<th>2</th>

<td>price</td>

<td>Price of each home sold</td>

</tr>

<tr>

<th>3</th>

<td>bedrooms</td>

<td>Number of bedrooms</td>

</tr>

<tr>

<th>4</th>

<td>bathrooms</td>

<td>Number of bathrooms, where .5 accounts for a room with a toilet but no shower</td>

</tr>

<tr>

<th>5</th>

<td>sqft_living</td>

<td>Square footage of the apartments interior living space</td>

</tr>

<tr>

<th>6</th>

<td>sqft_lot</td>

<td>Square footage of the land space</td>

</tr>

<tr>

<th>7</th>

<td>floors</td>

<td>Number of floors</td>

</tr>

<tr>

<th>8</th>

<td>waterfront</td>

<td>A dummy variable for whether the apartment was overlooking the waterfront or not</td>

</tr>

<tr>

<th>9</th>

<td>view</td>

<td>An index from 0 to 4 of how good the view of the property was</td>

</tr>

<tr>

<th>10</th>

<td>condition</td>

<td>An index from 1 to 5 on the condition of the apartment</td>

</tr>

<tr>

<th>11</th>

<td>grade</td>

<td>An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high-quality level of construction and design</td>

</tr>

<tr>

<th>12</th>

<td>sqft_above</td>

<td>The square footage of the interior housing space that is above ground level</td>

</tr>

<tr>

<th>13</th>

<td>sqft_basement</td>

<td>The square footage of the interior housing space that is below ground level</td>

</tr>

<tr>

<th>14</th>

<td>yr_built</td>

<td>The year the house was initially built</td>

</tr>

<tr>

<th>15</th>

<td>yr_renovated</td>

<td>The year of the house’s last renovation</td>

</tr>

<tr>

<th>16</th>

<td>zipcode</td>

<td>What zipcode area the house is in</td>

</tr>

<tr>

<th>17</th>

<td>lat</td>

<td>Latitude</td>

</tr>

<tr>

<th>18</th>

<td>long</td>

<td>Longitude</td>

</tr>

<tr>

<th>19</th>

<td>sqft_living15</td>

<td>The square footage of interior housing living space for the nearest 15 neighbors</td>

</tr>

<tr>

<th>20</th>

<td>sqft_lot15</td>

<td>The square footage of the land lots of the nearest 15 neighbors</td>

</tr>

</tbody>

</table>

## Project 3: Loan Repaid Status Prediction using Neural Networks

### Description

Data from Kaggle:

https://www.kaggle.com/datasets/wordsforthewise/lending-club

#### Feature Columns

<table border="1" class="dataframe">

<thead>

<tr style="text-align: right;">

<th></th>

<th>Features</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<th>0</th>

<td>loan_amnt</td>

<td>The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.</td>

</tr>

<tr>

<th>1</th>

<td>term</td>

<td>The number of payments on the loan. Values are in months and can be either 36 or 60.</td>

</tr>

<tr>

<th>2</th>

<td>int_rate</td>

<td>Interest Rate on the loan</td>

</tr>

<tr>

<th>3</th>

<td>installment</td>

<td>The monthly payment owed by the borrower if the loan originates.</td>

</tr>

<tr>

<th>4</th>

<td>grade</td>

<td>LC assigned loan grade</td>

</tr>

<tr>

<th>5</th>

<td>sub_grade</td>

<td>LC assigned loan subgrade</td>

</tr>

<tr>

<th>6</th>

<td>emp_title</td>

<td>The job title supplied by the Borrower when applying for the loan.*</td>

</tr>

<tr>

<th>7</th>

<td>emp_length</td>

<td>Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.</td>

</tr>

<tr>

<th>8</th>

<td>home_ownership</td>

<td>The home ownership status provided by the borrower during registration or obtained from the credit report. Our values are: RENT, OWN, MORTGAGE, OTHER</td>

</tr>

<tr>

<th>9</th>

<td>annual_inc</td>

<td>The self-reported annual income provided by the borrower during registration.</td>

</tr>

<tr>

<th>10</th>

<td>verification_status</td>

<td>Indicates if income was verified by LC, not verified, or if the income source was verified</td>

</tr>

<tr>

<th>11</th>

<td>issue_d</td>

<td>The month which the loan was funded</td>

</tr>

<tr>

<th>12</th>

<td>loan_status</td>

<td>Current status of the loan</td>

</tr>

<tr>

<th>13</th>

<td>purpose</td>

<td>A category provided by the borrower for the loan request.</td>

</tr>

<tr>

<th>14</th>

<td>title</td>

<td>The loan title provided by the borrower</td>

</tr>

<tr>

<th>15</th>

<td>zip_code</td>

<td>The first 3 numbers of the zip code provided by the borrower in the loan application.</td>

</tr>

<tr>

<th>16</th>

<td>addr_state</td>

<td>The state provided by the borrower in the loan application</td>

</tr>

<tr>

<th>17</th>

<td>dti</td>

<td>A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.</td>

</tr>

<tr>

<th>18</th>

<td>earliest_cr_line</td>

<td>The month the borrower's earliest reported credit line was opened</td>

</tr>

<tr>

<th>19</th>

<td>open_acc</td>

<td>The number of open credit lines in the borrower's credit file.</td>

</tr>

<tr>

<th>20</th>

<td>pub_rec</td>

<td>Number of derogatory public records</td>

</tr>

<tr>

<th>21</th>

<td>revol_bal</td>

<td>Total credit revolving balance</td>

</tr>

<tr>

<th>22</th>

<td>revol_util</td>

<td>Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.</td>

</tr>

<tr>

<th>23</th>

<td>total_acc</td>

<td>The total number of credit lines currently in the borrower's credit file</td>

</tr>

<tr>

<th>24</th>

<td>initial_list_status</td>

<td>The initial listing status of the loan. Possible values are – W, F</td>

</tr>

<tr>

<th>25</th>

<td>application_type</td>

<td>Indicates whether the loan is an individual application or a joint application with two co-borrowers</td>

</tr>

<tr>

<th>26</th>

<td>mort_acc</td>

<td>Number of mortgage accounts.</td>

</tr>

<tr>

<th>27</th>

<td>pub_rec_bankruptcies</td>

<td>Number of public record bankruptcies</td>

</tr>

</tbody>

</table>
