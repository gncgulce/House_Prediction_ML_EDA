<div style='background-color: #6c94dc; padding: 10px'>
    
<h1> Business Problem</h1>  

A machine learning model is expected to be developed to predict customers who will leave the company.
    
</div>

![House](https://github.com/user-attachments/assets/55e462df-0aaa-4f66-b3fd-e8d9e69d1fdf)




<div style='background-color: #6c94dc; padding: 10px'>
    
<h1>Dataset</h1>  

This dataset contains housing data, which will be used for a separate analysis on property sales prediction.
<blockquote><strong><h1>Details</h1></strong></blockquote>
<strong>80 Variables | Various Observations</strong>
    
</div>

<table style="width:100%; border: 1px solid #ddd; border-collapse: collapse;">
  <colgroup>
    <col style="width: 18%;">
    <col style="width: 70%;">
  </colgroup>
  <tr style="background-color: #6c94dc;">
    <th style="border: 1px solid #ddd; font-size: 13px; padding: 8px; text-align: left;">Variable</th>
    <th style="border: 1px solid #ddd; font-size: 13px; padding: 8px; text-align: left;">Description</th>
  </tr> 
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">SalePrice</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">The property's sale price in dollars. This is the target variable that you're trying to predict.</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">MSSubClass</td> 
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">The building class</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">MSZoning</td> 
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">The general zoning classification</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">LotFrontage</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Linear feet of street connected to property</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">LotArea</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Lot size in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Street</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of road access</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Alley</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of alley access</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">LotShape</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">General shape of property</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">LandContour</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Flatness of the property</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Utilities</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of utilities available</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">LotConfig</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Lot configuration</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">LandSlope</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Slope of property</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Neighborhood</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Physical locations within Ames city limits</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Condition1</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Proximity to main road or railroad</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Condition2</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Proximity to main road or railroad (if a second is present)</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BldgType</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of dwelling</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">HouseStyle</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Style of dwelling</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">OverallQual</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Overall material and finish quality</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">OverallCond</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Overall condition rating</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">YearBuilt</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Original construction date</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">YearRemodAdd</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Remodel date</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">RoofStyle</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of roof</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">RoofMatl</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Roof material</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Exterior1st</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Exterior covering on house</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Exterior2nd</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Exterior covering on house (if more than one material)</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">MasVnrType</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Masonry veneer type</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">MasVnrArea</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Masonry veneer area in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">ExterQual</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Exterior material quality</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">ExterCond</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Present condition of the material on the exterior</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Foundation</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of foundation</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtQual</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Height of the basement</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtCond</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">General condition of the basement</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtExposure</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Walkout or garden level basement walls</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtFinType1</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Quality of basement finished area</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtFinSF1</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type 1 finished square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtFinType2</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Quality of second finished area (if present)</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtFinSF2</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type 2 finished square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtUnfSF</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Unfinished square feet of basement area</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">TotalBsmtSF</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Total square feet of basement area</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Heating</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of heating</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">HeatingQC</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Heating quality and condition</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">CentralAir</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Central air conditioning</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Electrical</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Electrical system</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">1stFlrSF</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">First Floor square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">2ndFlrSF</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Second floor square feet</td>
  </tr>
    <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">LowQualFinSF</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Low quality finished square feet (all floors)</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GrLivArea</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Above grade (ground) living area square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtFullBath</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Basement full bathrooms</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">BsmtHalfBath</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Basement half bathrooms</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">FullBath</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Full bathrooms above grade</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">HalfBath</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Half baths above grade</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Bedroom</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Bedrooms above grade (does NOT include basement bedrooms)</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Kitchen</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Kitchens above grade</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">KitchenQual</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Kitchen quality</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">TotRmsAbvGrd</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Total rooms above grade (does not include bathrooms)</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Functional</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Home functionality rating</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Fireplaces</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Number of fireplaces</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">FireplaceQu</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Fireplace quality</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GarageType</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Garage location</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GarageYrBlt</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Year garage was built</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GarageFinish</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Interior finish of the garage</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GarageCars</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Size of garage in car capacity</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GarageArea</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Size of garage in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GarageQual</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Garage quality</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">GarageCond</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Garage condition</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">PavedDrive</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Paved driveway</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">WoodDeckSF</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Wood deck area in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">OpenPorchSF</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Open porch area in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">EnclosedPorch</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Enclosed porch area in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">3SsnPorch</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Three season porch area in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">ScreenPorch</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Screen porch area in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">PoolArea</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Pool area in square feet</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">PoolQC</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Pool quality</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">Fence</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Fence quality</td>
  </tr>
  <tr style="background-color:#6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">MiscFeature</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Miscellaneous feature not covered in other categories</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">MiscVal</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Value of miscellaneous feature</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">MoSold</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Month sold</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">YrSold</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Year sold</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">SaleType</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Type of sale</td>
  </tr>
  <tr style="background-color: #6c94dc;">
    <td style="border: 1px solid #ddd; padding: 8px;">SaleCondition</td>
    <td style="border: 1px solid #ddd; background-color: #b1cffc; padding: 8px;">Condition of sale</td>
  </tr>
</table>

</body>
</html>
