Library used to check and update notebooks in the HBP Collaboratory. 

The library is using the SHA of the current notebook and its location to download and verify the most recent version of the notebook from github. 
If the version are different the user has the choice to replace the current notebook with the most recent version. In that case the notebook is replaced in the Collab storage, and the current Collab page is being reloaded. 

Note: This library works only within a Jupyter notebook.