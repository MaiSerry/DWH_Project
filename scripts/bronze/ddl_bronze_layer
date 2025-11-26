
IF OBJECT_ID('bronze.crm_cust_info','U') IS NOT NULL
	Drop table bronze.crm_cust_info
	go
create table bronze.crm_cust_info(
cust_id int ,
cst_key NVARCHAR(50),
cst_firstname NVARCHAR(50),
cst_lastname NVARCHAR(50),
cst_marital_status NVARCHAR(50),
cst_gndr NVARCHAR(50),
cst_create_date Date
);
IF OBJECT_ID('bronze.crm_prd_info','U') IS NOT NULL
	Drop table bronze.crm_prd_info
	go
create table bronze.crm_prd_info(
prd_id int,
prd_key NVARCHAR(50),
prd_nm NVARCHAR(50),
prd_cost int,
prd_line NVARCHAR(50),
prd_start_dt DateTime,
prd_end_dt DateTime
);
IF OBJECT_ID('bronze.crm_sales_details','U') IS NOT NULL
	Drop table bronze.crm_sales_details
	go
create table bronze.crm_sales_details(
sls_ord_num NVARCHAR(50),
sls_prd_key NVARCHAR(50),
sls_cust_id int,
sls_order_dt int,
sls_ship_dt int,
sls_due_dt int,
sls_sales  int ,
sls_quantity int ,
sls_price int 
);

IF OBJECT_ID('bronze.erp_cust_az12','U') IS NOT NULL
	Drop table bronze.erp_cust_az12
	go
Create table bronze.erp_cust_az12(
	cid NVARCHAR(50),
	bdate DATE,
	gen NVARCHAR(50)
);
IF OBJECT_ID('bronze.erp_loc_a101','U') IS NOT NULL
	Drop table bronze.erp_loc_a101
	go
Create table bronze.erp_loc_a101(
	cid NVARCHAR(50),
	center NVARCHAR(50)
);
IF OBJECT_ID('bronze.erp_px_cat_g172','U') IS NOT NULL
	Drop table bronze.erp_px_cat_g172
	go
Create table bronze.erp_px_cat_g172(
	id NVARCHAR(50),
	cat NVARCHAR(50),
	subcat NVARCHAR(50),
	maintenance NVARCHAR(50)
);



