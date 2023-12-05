# Veeam App for ServiceNow
The Veeam App for ServiceNow is a native ServiceNow application developed and supported as a close collaboration between Veeam and a 3rd-party ServiceNow Build/Veeam partner with the eventual goal to publish the application into the ServiceNow marketplace.  We are publishing the application here to get initial feedback on features and additional capabilities.
Any users that would like to install it are welcome to do so, however, note that support is provided only to users with Advanced or Premium edition licenses.  Please see the support section below for more details.

**Important Note**\
Veeam offers two different methods for organizations to integrate Veeam products with ServiceNow based on their specific needs.

### Veeam ONE
Starting with the 12.1 release of Veeam ONE it is possible to configure alerts to be sent directly to ServiceNow to automatically open and close incidents.  This integration is very simple and requires configuration of just a few parameters to receive rich incident information from any event from which Veeam ONE can generate an alert.  For many users, this is the easiest method to widely monitor and report on Veeam events in ServiceNow.

### Veeam App for ServiceNow
The project in this repository is targeted at organizations that want to pursue a more integrated approach, synchronizing data from Veeam directly into ServiceNow, and providing visibility of backup status, as well as provisioning of backups, directly into the ServiceNow user experience. To get full use of this capability will likely require some customization and additional integration work on the ServiceNow side thus it is targeted at organizations with ServiceNow implementation teams already in place.

The current release of the app focuses primarily on VMware capabilities; however, we are very interested in expanding the capabilities and job types covered in future versions and are happy to collaborate with anyone who has specific requirements.  Please feel free to open an issue here or reach out directly to tom.sightler@veeam.com if you have specific needs that you would like to discuss.

Currently the following features are supported:
* Simple, guided setup
* Synchronization of VMware backup jobs from multiple Veeam Backup & Replication servers
* Ability to automatically create incidents on job failures
* Synchronization of VM restore points for visibility in ServiceNow
* Simple dashboard view showing success/warning/failure status for previous 14 days, including click into details for failures or created incidents
* Select Backup Jobs for use as a Backup Template
* Backup Templates can be leveraged as part of workflow to add VMs to a job or move VMs between jobs

## 📗 Documentation
All documentation is available in the [docs folder](https://github.com/VeeamHub/veeam-servicenow/tree/main/docs) of this repository.

## 🤝🏾 Support
Currently, support is provided via Github and users can leverage [issues](https://github.com/VeeamHub/veeam-servicenow) to request assistance, report any bugs, or submit any feature requests.
As this is the initial release, if you are looking for an official evaluation, please reach out to your sales team and they will engage the correct resources directly.

## 🤔 Questions
If you have any questions or something is unclear, please don't hesitate to [create an issue](https://github.com/VeeamHub/veeam-servicenow/issues/new/choose) or reach out directly to the project owner tom.sightler@veeam.com and let us know.

