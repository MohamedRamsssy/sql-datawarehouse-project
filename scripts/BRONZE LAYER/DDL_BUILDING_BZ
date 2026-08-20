THIS  SCRIPT FOR BUILDING BRONZE LAYER TABLES ACCORDING TO  SOURCE DATA ,
ALSO SHOWING EACH DATA TYBE 
----------------------------------
CREATE table Bronze.crm_cust_info (

	 cst_id int ,
	 cst_key Nvarchar (50),
	 cst_firstname Nvarchar (50), 
	 cst_lastname Nvarchar (50),
	 cst_marital_status Nvarchar (50),
	 cst_gndr Nvarchar (50),
	 cst_create_date DATE 

	 );
 
CREATE table Bronze.crm_prd_info (

	prd_id int,
	prd_key Nvarchar (50),
	prd_nm Nvarchar (50), 
	prd_cost Nvarchar (50),
	prd_line Nvarchar (50),
	prd_start_dt date,
	prd_end_dt date 

	);

CREATE table Bronze.crm_sales_details (

	sls_ord_num Nvarchar (50) ,
	sls_prd_key Nvarchar (50),
	sls_cust_id int,
	sls_order_dt DATE,
	sls_ship_dt DATE,
	sls_due_dt DATE,
	sls_sales int,
	sls_quantity int,
	sls_price int

	);
	
CREATE table Bronze.erp_CUST_AZ12 (

	CID Nvarchar (50),
	BDATE date,
	GEN Nvarchar (50)

	);

CREATE table Bronze.erp_LOC_A101 (

	CID Nvarchar (50),
	CNTRY Nvarchar (50)

	);

CREATE table Bronze.erp_PX_CAT_G1V2 (

	ID Nvarchar (50) ,
	CAT Nvarchar (50),
	SUBCAT Nvarchar (50),
	MAINTENANCE Nvarchar (50) 

	);




