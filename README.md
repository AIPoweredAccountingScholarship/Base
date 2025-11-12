# AI-Powered Accounting Scholarship

We use a large language model (LLM) to conduct empirical accounting research on the causal effect of securities regulation on voluntary disclosure. 

We start by using Claude 4 Sonnet to identify securities regulations both in the U.S. and the non-U.S. jurisdictions. We then use the LLM to map each regulation to the channel on how a particular securities regulation may affect voluntary disclosure. These channels include litigation risk, corporate governance, proprietary costs, information asymmetry, protection of unsophisticated investors, equity issuance, and reputation risk. A securities regulation can affect voluntary disclosure through more than one channel and the LLM writes a separate academic paper for each securities regulation-voluntary disclosure channel combination. 

The LLM generates 212 academic papers with statistically significant results examining how mandatory securities regulations influence U.S. firms' voluntary disclosure practices.

The AI-generated papers can be found in the Manuscripts folders. There are 74 AI-generated papers for U.S. securities laws and 138 AI-generated papers for non-U.S. securities regulations. The papers were generated using Claude 4 Sonnet and Python. 

Below is a mapping of research tasks to their corresponding Jupyter files and output folders.

| Research Task                                                       | Setting: U.S. laws | Setting: non-U.S. laws | Jupyter File                                                               | Output Folder                                                                     |
| ------------------------------------------------------------------- | ------------------ | ---------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Collection of shocks (U.S.)                                         | Y                  |                        | Master File_Federal Securities Laws                                        | Output_Master File_Federal Securities Laws                                        |
| Collection of shocks (non-U.S.)                                     |                    | Y                      | Master File_Global_Securities Laws                                         | Output_Master File_Global_Securities Laws                                         |
| Generate U.S. papers                                                | Y                  |                        | Master File_Federal Securities Laws                                        | Output_Master File_Federal Securities Laws                                        |
| Generate non-U.S. papers                                            |                    | Y                      | Master File_Global_Securities Laws                                         | Output_Master File_Global_Securities Laws                                         |
| Comparing LLMs collection of shocks (U.S.)                          | Y                  |                        | Master File_LLM Performance (ChatGPT & Gemini)_Identify_Federal Securities | Output_Master File_LLM Performance (ChatGPT & Gemini)_Identify_Federal Securities |
| Comparing LLMs collection of shocks (non-U.S.)                      |                    | Y                      | Master File_LLM Performance (ChatGPT & Gemini)_Identify_Global Securities  | Output_Master File_LLM Performance (ChatGPT & Gemini)_Identify_Global Securities  |
| Alternative programming                                             | Y                  |                        | Master File_Alternative Programming                                        | Output_Master File_Alternative Programming                                        |
| Spurious correlation test (U.S.)                                    | Y                  |                        | Master File_Federal Securities Laws_Spurious Correlation Assessment        | Output_Master File_Federal Securities Laws_Spurious Correlation Assessment        |
| Spurious correlation test (non-U.S.)                                |                    | Y                      | Master File_Global Securities Laws_Spurious Correlation Assessment         | Output_Master File_Global Securities Laws_Spurious Correlation Assessment         |
| Data collection after knowledge cutoff date - Collections of shocks | Y                  |                        | Master File_Data Collection Outside of Training Data                       | Output_Master File_Data Collection Outside of Training Data                       |
| Data collection after knowledge cutoff date - Generate papers       | Y                  |                        | Master File_Data Collection Outside of Training Data                       | Output_Master File_Data Collection Outside of Training Data                       |
| State-level collection of shocks                                    | Y                  |                        | Master File_State-Level Securities Laws                                    | Output_Master File_State-Level Securities Laws                                    |
| Generate state-level papers                                         | Y                  |                        | Master File_State-Level Securities Laws                                    | Output_Master File_State-Level Securities Laws                                    |
| Research ideas                                                      | Y                  |                        | Master File_Research Ideas                                                 | Output_Master File_Research Ideas                                                 |


Please cite this work as follows: Ciconte, Rozario, and Urcan (2025). Using AI to identify exogenous shocks and conduct archival accounting research. Working Paper. 
