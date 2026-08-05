# Dissertation Documents 
# Code Run Steps using the Colab Application
This Repository contains all important dissertation documents, such as code and a full information Word document about the project/dissertation.
# Running the Python Notebooks in Google Colab

Follow the steps below to execute the Python notebooks in the correct sequence.

## Step 1: Establish SAP CPI Connectivity

1. Open the notebook:
   - `Connectivity_Establishment_SAP_CPI_API_Payload_test_1.ipynb`
2. Click **Open in Colab**.
3. In the top-right corner, click **Connect** to establish the connection between **SAP CPI** and **Google Colab**.

---

## Step 2: Validate the API Connection

1. Open the notebook:
   - `SAP_CPI_API_sending_wrong_payload_test_2.ipynb`
2. Click **Open in Colab**.
3. Click **Connect** in the top-right corner.
4. Once connected, the notebook will validate the connection and prepare the environment for code execution.

---

## Step 3: Run the Payload Validation and Correction Engine

1. Open the notebook:
   - `Date_Validation_Part_3_API_Correction_Engine.ipynb`
2. Click **Open in Colab**.
3. Click **Connect** in the top-right corner.
4. Navigate to **Section 20 (Payload 1)** in the notebook.
5. From the **Runtime** menu, select:
   - **Run cell and below**
6. Wait for the execution to complete.

---

## Output

After execution finishes, scroll to the bottom of the notebook to view the results.

The output includes:

- ✅ Success or Failure status
- ❌ Error details (if any)
- 🔍 Payload validation results
- 🔄 Automatic correction details (when applicable)

---

## Execution Order

Run the notebooks in the following order:

1. `Connectivity_Establishment_SAP_CPI_API_Payload_test_1.ipynb`
2. `SAP_CPI_API_sending_wrong_payload_test_2.ipynb`
3. `Date_Validation_Part_3_API_Correction_Engine.ipynb`

> **Important:** Execute the notebooks in the above order to ensure that the SAP CPI connection is established and validated before running the payload validation and correction engine.
