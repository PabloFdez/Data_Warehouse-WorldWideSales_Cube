# Microsoft World Wide Importers Cube

Originally published at: https://dev.azure.com/pfernandezdiaz/PFD_Cube_A2

## Analytical Services attributes:

The following Dimensions and Measure Groups are implemented on the cube:

| Dimension  |
|---|
| Delivery_Date  |
| Order_Date | 
| Received_Date |
| Invoice_Date  |
| Customer  |
| Stock_Item  |
| Bill_To_Customer  |
| City  |
| Employee  |

| Measure Group |
|---|
| Sales  | 
| Order  | 
| Purchase  | 

The structure of the Data Source View (including the relationships between all the tables used) is the following:

![image](https://github.com/PabloFdez/Data_Warehouse-WorldWideSales_Cube/blob/master/pictures/structure.png)

The final cube created (including all its dimensions and MG and the attributes used to relate them) is shown bellow:

![image](https://github.com/PabloFdez/Data_Warehouse-WorldWideSales_Cube/blob/master/pictures/cube.png)
