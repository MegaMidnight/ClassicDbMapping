# Classic Database Mappings

## **Projects Table**

| **Source Table**                      | **Foreign Key Mapping**                                  |
|---------------------------------------|----------------------------------------------------------|
| **analysis_report_cron**              | `project_id` → `projects.id`                             |
| **ar_report_cron**                    | `project_id` → `projects.id`                             |
| **avg_cost**                          | `project_id` → `projects.id`                             |
| **ca_report_data**                    | `project_id` → `projects.id`                             |
| **calendar**                          | `project_id` → `projects.id`                             |
| **chap_alt**                          | `project_id` → `projects.id`                             |
| **closed_labor**                      | `project_id` → `projects.id`                             |
| **closed_project_notes**              | `project_id` → `projects.id`                             |
| **commission_report_extra_data**      | `project_id` → `projects.id`                             |
| **cost_to_date_report**               | `project_id` → `projects.id`                             |
| **costing_history**                   | `project_id` → `projects.id`                             |
| **costing_history_admin_print**       | `project_id` → `projects.id`                             |
| **costing_history_labor**             | `project_id` → `projects.id`                             |
| **costing_purchase_orders**           | `project_id` → `projects.id`                             |
| **department_hours_report**           | `project_id` → `projects.id`                             |
| **designs**                           | `project_id` → `projects.id`                             |
| **dh_actual**                         | `project_id` → `projects.id`                             |
| **dh_estimates**                      | `project_id` → `projects.id`                             |
| **dh_over_budget_alerts**             | `project_id` → `projects.id`                             |
| **document_file_folders**             | `project_id` → `projects.id`                             |
| **documents**                         | `project_id` → `projects.id`                             |
| **electronic_time_cards**             | `project_id` → `projects.id`                             |
| **electronic_time_cards_temp**        | `project_id` → `projects.id`                             |
| **email_tracking**                    | `project_id` → `projects.id`                             |
| **estimates**                         | `project_id` → `projects.id`                             |
| **file_folders**                      | `project_id` → `projects.id`                             |
| **files**                             | `project_id` → `projects.id`                             |
| **job_status**                        | `project_id` → `projects.id`                             |
| **job_status_notes**                  | `project_id` → `projects.id`                             |
| **js_temp**                           | `project_id` → `projects.id`                             |
| **lar**                               | `project_id` → `projects.id`                             |
| **milestones**                        | `project_id` → `projects.id`                             |
| **production_files**                  | `project_id` → `projects.id`                             |
| **project_contacts**                  | `project_id` → `projects.id`                             |
| **project_status_cron**               | `project_id` → `projects.id`                             |
| **projects**                          | `project_id` → `projects.id` *(Possible self-reference)* |
| **projects_favorites**                | `project_id` → `projects.id`                             |
| **proposals**                         | `project_id` → `projects.id`                             |
| **purchase_order_items**              | `project_id` → `projects.id`                             |
| **purchase_order_outsource**          | `project_id` → `projects.id`                             |
| **purchase_orders**                   | `project_id` → `projects.id`                             |
| **purchasing**                        | `project_id` → `projects.id`                             |
| **purchasing_allocation**             | `project_id` → `projects.id`                             |
| **purchasing_line_items**             | `project_id` → `projects.id`                             |
| **purchasing_preallocation**          | `project_id` → `projects.id`                             |
| **quickbooks_creditmemo**             | `project_id` → `projects.id`                             |
| **quickbooks_invoice**                | `project_id` → `projects.id`                             |
| **quickbooks_purchaseorder**          | `project_id` → `projects.id`                             |
| **quickbooks_purchaseorder_lineitem** | `project_id` → `projects.id`                             |
| **sales_contacts**                    | `project_id` → `projects.id`                             |
| **sales_conversations**               | `project_id` → `projects.id`                             |
| **shop_orders**                       | `project_id` → `projects.id`                             |
| **site_photos**                       | `project_id` → `projects.id`                             |
| **tasks**                             | `project_id` → `projects.id`                             |
| **temp_estimates_time**               | `project_id` → `projects.id`                             |
| **timecards**                         | `project_id` → `projects.id`                             |
| **unpaid_commission_report**          | `project_id` → `projects.id`                             |
| **unpaid_split_commission_report**    | `project_id` → `projects.id`                             |
| **user_tasks**                        | `project_id` → `projects.id`                             |
| **wip**                               | `project_id` → `projects.id`                             |
| **wip_project_labor_summary**         | `project_id` → `projects.id`                             |

---

## **Employees Table**

| **Source Table**               | **Foreign Key Mapping**                                    |
|--------------------------------|------------------------------------------------------------|
| **closed_labor**               | `employee_id` → `employees.id`                             |
| **designs**                    | `employee_id` → `employees.id`                             |
| **dh_over_budget_alerts**      | `employee_id` → `employees.id`                             |
| **documents**                  | `employee_id` → `employees.id`                             |
| **electronic_time_cards**      | `employee_id` → `employees.id`                             |
| **electronic_time_cards_temp** | `employee_id` → `employees.id`                             |
| **email_tracking**             | `employee_id` → `employees.id`                             |
| **employee_calendar**          | `employee_id` → `employees.id`                             |
| **employee_leaves**            | `employee_id` → `employees.id`                             |
| **employee_notes**             | `employee_id` → `employees.id`                             |
| **employee_permissions**       | `employee_id` → `employees.id`                             |
| **employee_rates**             | `employee_id` → `employees.id`                             |
| **employee_report_args**       | `employee_id` → `employees.id`                             |
| **employees**                  | `employee_id` → `employees.id` *(Possible self-reference)* |
| **files**                      | `employee_id` → `employees.id`                             |
| **president_message_read**     | `employee_id` → `employees.id`                             |
| **projects_favorites**         | `employee_id` → `employees.id`                             |
| **task_replies**               | `employee_id` → `employees.id`                             |
| **tasks**                      | `employee_id` → `employees.id`                             |
| **timecards**                  | `employee_id` → `employees.id`                             |
| **wip_project_labor_summary**  | `employee_id` → `employees.id`                             |

---

## **Customers Table**

| **Source Table**               | **Foreign Key Mapping**        |
|--------------------------------|--------------------------------|
| **ccwnames**                   | `customer_id` → `customers.id` |
| **customer_contact**           | `customer_id` → `customers.id` |
| **customer_sign_standards**    | `customer_id` → `customers.id` |
| **digital_signature_initials** | `customer_id` → `customers.id` |
| **project_status_cron**        | `customer_id` → `customers.id` |

---

## **Vendors Table**

| **Source Table**             | **Foreign Key Mapping**                                |
|------------------------------|--------------------------------------------------------|
| **purchase_orders**          | `vendor_id` → `vendors.id`                             |
| **purchase_orders**          | `vendor_contact_id` → `vendor_contact.id`              |
| **purchase_order_outsource** | `purchase_order_id` → `purchase_orders.id`             |
| **quickbooks_purchaseorder** | `vendor_id` → `vendors.id`                             |
| **quickbooks_purchaseorder** | `vendor_contact_id` → `vendor_contact.id`              |
| **vendor_contact**           | `vendor_id` → `vendors.id`                             |
| **vcwnames**                 | `vendor_id` → `vendors.id`                             |
| **vendors**                  | `vendor_id` → `vendors.id` *(Possible self-reference)* |
| **vendors**                  | `tax_id` → `tax.id`                                    |

---

## **Designs Table**

| **Source Table**             | **Foreign Key Mapping**                                |
|------------------------------|--------------------------------------------------------|
| **design_comments**          | `design_link_id` → `design_links.id`                   |
| **design_links**             | `design_id` → `designs.id`                             |
| **designs**                  | `design_id` → `designs.id` *(Possible self-reference)* |
| **designs**                  | `employee_id` → `employees.id`                         |
| **designs**                  | `project_id` → `projects.id`                           |
| **estimates**                | `design_id` → `designs.id`                             |
| **files**                    | `design_id` → `designs.id`                             |
| **purchase_orders**          | `design_id` → `designs.id`                             |
| **quickbooks_purchaseorder** | `design_id` → `designs.id`                             |

---

## **Invoices Table**

| **Source Table**                 | **Foreign Key Mapping**                                  |
|----------------------------------|----------------------------------------------------------|
| **ar_report_cron**               | `invoice_id` → `invoices.id`                             |
| **commission_report_extra_data** | `invoice_id` → `invoices.id`                             |
| **invoice_line_items**           | `invoice_id` → `invoices.id`                             |
| **invoice_payments**             | `invoice_id` → `invoices.id`                             |
| **invoices**                     | `invoice_id` → `invoices.id` *(Possible self-reference)* |
| **invoices**                     | `project_id` → `projects.id`                             |
| **line_items_copy_history**      | `invoice_id` → `invoices.id`                             |
| **qbo_credit_memos**             | `invoice_id` → `invoices.id`                             |
| **qbo_payments**                 | `invoice_id` → `invoices.id`                             |
| **qbo_payments_temp**            | `invoice_id` → `invoices.id`                             |
| **quickbooks_creditmemo**        | `invoice_id` → `invoices.id`                             |
| **quickbooks_invoice**           | `invoice_id` → `invoices.id`                             |

---

## **Estimates Table**

| **Source Table**         | **Foreign Key Mapping**                                    |
|--------------------------|------------------------------------------------------------|
| **dh_estimates**         | `estimate_id` → `estimates.id`                             |
| **estimate_markup_row**  | `estimate_id` → `estimates.id`                             |
| **estimates**            | `estimate_id` → `estimates.id` *(Possible self-reference)* |
| **estimates**            | `project_id` → `projects.id`                               |
| **estimates_buyouts**    | `estimate_id` → `estimates.id`                             |
| **estimates_commission** | `estimate_id` → `estimates.id`                             |
| **estimates_machines**   | `estimate_id` → `estimates.id`                             |
| **estimates_time**       | `estimate_id` → `estimates.id`                             |
| **temp_estimates_time**  | `estimate_id` → `estimates.id`                             |

---

## **Files Table**

| **Source Table**    | **Foreign Key Mapping**                            |
|---------------------|----------------------------------------------------|
| **design_approval** | `file_id` → `files.id`                             |
| **design_comments** | `file_id` → `files.id`                             |
| **files**           | `file_id` → `files.id` *(Possible self-reference)* |
| **files**           | `design_id` → `designs.id`                         |
| **files**           | `employee_id` → `employees.id`                     |
| **files**           | `project_id` → `projects.id`                       |

---

## **Tasks Table**

| **Source Table** | **Foreign Key Mapping**        |
|------------------|--------------------------------|
| **task_replies** | `task_id` → `tasks.id`         |
| **tasks**        | `employee_id` → `employees.id` |
| **tasks**        | `project_id` → `projects.id`   |
| **user_tasks**   | `task_id` → `tasks.id`         |

---

## **Purchase Orders Table**

| **Source Table**                      | **Foreign Key Mapping**                                                |
|---------------------------------------|------------------------------------------------------------------------|
| **costing_materials**                 | `purchase_order_id` → `purchase_orders.id`                             |
| **costing_purchase_orders**           | `purchase_order_id` → `purchase_orders.id`                             |
| **purchase_order_items**              | `purchase_order_id` → `purchase_orders.id`                             |
| **purchase_order_outsource**          | `purchase_order_id` → `purchase_orders.id`                             |
| **purchase_orders**                   | `purchase_order_id` → `purchase_orders.id` *(Possible self-reference)* |
| **purchasing**                        | `purchase_order_id` → `purchase_orders.id`                             |
| **quickbooks_purchaseorder**          | `purchase_order_id` → `purchase_orders.id`                             |
| **quickbooks_purchaseorder_lineitem** | `purchase_order_id` → `purchase_orders.id`                             |

---

## **Labor Table**

| **Source Table**        | **Foreign Key Mapping** |
|-------------------------|-------------------------|
| **estimates_machines**  | `labor_id` → `labor.id` |
| **estimates_time**      | `labor_id` → `labor.id` |
| **temp_dept_hours**     | `labor_id` → `labor.id` |
| **temp_estimates_time** | `labor_id` → `labor.id` |

---

## **Leads Table**

| **Source Table**    | **Foreign Key Mapping**                            |
|---------------------|----------------------------------------------------|
| **leads**           | `lead_id` → `leads.id` *(Possible self-reference)* |
| **leads**           | `project_contact_id` → `project_contacts.id`       |
| **leads_notes**     | `lead_id` → `leads.id`                             |
| **leads_reminders** | `lead_id` → `leads.id`                             |
| **projects**        | `lead_id` → `leads.id`                             |

---

## **Project Contacts Table**

| **Source Table**     | **Foreign Key Mapping**                      |
|----------------------|----------------------------------------------|
| **leads**            | `project_contact_id` → `project_contacts.id` |
| **projects**         | `project_contact_id` → `project_contacts.id` |
| **project_contacts** | `project_id` → `projects.id`                 |

---

## **Milestones Table**

| **Source Table**    | **Foreign Key Mapping**                                      |
|---------------------|--------------------------------------------------------------|
| **milestone_notes** | `milestone_id` → `milestones.id`                             |
| **milestones**      | `milestone_id` → `milestones.id` *(Possible self-reference)* |
| **milestones**      | `project_id` → `projects.id`                                 |

---

## **Inventory Table**

| **Source Table**         | **Foreign Key Mapping**                                     |
|--------------------------|-------------------------------------------------------------|
| **costing_materials**    | `inventory_id` → `inventory.id`                             |
| **estimates_material**   | `inventory_id` → `inventory.id`                             |
| **inventory**            | `inventory_id` → `inventory.id` *(Possible self-reference)* |
| **misc_materials**       | `inventory_id` → `inventory.id`                             |
| **purchase_order_items** | `inventory_id` → `inventory.id`                             |

---

## **Purchasing Table**

| **Source Table**                      | **Foreign Key Mapping**                    |
|---------------------------------------|--------------------------------------------|
| **purchase_order_items**              | `purchasing_id` → `purchasing.id`          |
| **purchasing**                        | `purchase_order_id` → `purchase_orders.id` |
| **purchasing**                        | `project_id` → `projects.id`               |
| **purchasing_line_items**             | `project_id` → `projects.id`               |
| **quickbooks_purchaseorder_lineitem** | `purchasing_id` → `purchasing.id`          |

---

## **Other Tables and Relationships**

### **Digital Signatures**

| **Source Table**               | **Foreign Key Mapping**        |
|--------------------------------|--------------------------------|
| **digital_signature_initials** | `customer_id` → `customers.id` |
| **digital_signature_initials** | `document_id` → `documents.id` |

### **Documents Table**

| **Source Table**               | **Foreign Key Mapping**        |
|--------------------------------|--------------------------------|
| **digital_signature_initials** | `document_id` → `documents.id` |
| **documents**                  | `employee_id` → `employees.id` |
| **documents**                  | `project_id` → `projects.id`   |

### **Miscellaneous Relationships**

- **electronic_time_cards_settings** | `timezone_id` → `timezones.id`
- **quickbooks_purchaseorder_lineitem** | `qbo_account_id` → `qbo_accounts.id`
- **quickbooks_receivepayment** | `qbo_payment_method_id` → `qbo_payment_methods.id`
- **sign_criteria_docs** | `sign_criteria_id` → `sign_criteria.id`
- **site_photos_keywords** | `keyword_id` → `keywords.id`
- **vendors** | `tax_id` → `tax.id`