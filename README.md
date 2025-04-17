# Point of Sale (POS)

# POS Database Schema with Relationships
This project creates a Point of Sale (POS) database structure with properly defined relationships between the tables. The table creation follows this sequence:

  users → categories → products → customers → invoice → invoice_products

# Table Relationship Flow:

    - users – Stores user login/management info.

    - categories – Product categories linked to users.

    - products – Belongs to categories.

    - customers – End users who make purchases.

    - invoice – Stores sales records, linked to customers.

    - invoice_products – Stores individual product details per invoice.

# The following Scenario illustrate the relationships between the main tables in the POS system:
  
        1. users can manage multiple categories, products, customers, invoices, and invoice_products.

        2. Each category contains multiple products.

        3. customers can have multiple invoices.

        4. Each invoice contains multiple invoice_products, and each product listed is linked to a record in products.



        
