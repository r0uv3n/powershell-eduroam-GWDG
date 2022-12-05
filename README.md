# powershell-eduroam-GWDG

PowerShell script to install GWDG (University Göttingen and "Gesellschaft für wissenschaftliche Datenverarbeitung mbH Göttingen" in general) eduroam profile.

This is adapted from [Ramus Kriest's powershell-eduroam](https://github.com/rasmuskriest/powershell-eduroam).
### Installing

The actual installation is extremely easy: Just clone the repository and run `Install-Eduroam.ps1` from a PowerShell with elevated rights (you might need to [change the Execution Policy](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.security/set-executionpolicy?view=powershell-5.1)). You may also want to just clone the [original repository](https://github.com/rasmuskriest/powershell-eduroam) and then replace the `wlan_prof-0.xml` file with the version from this repository.

## Built With

* The included profile was extracted from the [eduroam CAT with University of Göttingen as selected institution](https://cat.eduroam.org/).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
