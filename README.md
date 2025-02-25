## Summary
This is an observation preparation tool for the VLTI UTs/ATs, whose packages include: [SCIFYsim](https://github.com/SCIFY-IvS/SCIFYsim) (the engine behind the tool), astropy & astroplan. The app has been created with [Streamlit](https://streamlit.io/).

### App preview
Below is a tab that displays the general information of the target of interest. On the left panel, the user is required to specify the desired VLTI array configuration, SIMBAD identifier of the target, and observation date. The planet RA and Dec offset are optional. 
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/pclp007/NOTT-observation-preparation-tool/blob/main/lib/images/NOTT_app_1.png)

Below is a tab that displays the throughput maps computed for three different input beam permutations.
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/pclp007/NOTT-observation-preparation-tool/blob/main/lib/images/NOTT_app_2.png)

Below is a tab that displays the SNR maps computed for three different input beam permutations.
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/pclp007/NOTT-observation-preparation-tool/blob/main/lib/images/NOTT_app_3.png)

### Acknowledgements

This project was funded by the European Union's Horizon 2020 research and innovation program under grant agreement No. 101004719.

This project has also received support from the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation program (grant agreement No 8660).

### How to run the app

1. Specify the file path of `config_file` in `NOTT_app_2.py`
2. The app will open in your default web browser with the following command `streamlit run NOTT_app_2.py`

#### Dependencies

[SCIFYsim](https://github.com/SCIFY-IvS/SCIFYsim) 
[kernuller](https://github.com/rlaugier/kernuller)
[xaosim](https://github.com/fmartinache/xaosim)
