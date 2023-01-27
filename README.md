# Sentinel_GeoIP_Homelab
Homelab that logs failed RDP connections based on IP and Geo locates them on a map.

This PS script will parse out Windows Event Log information from a vulnerable honeypot VM, specifically failed RDP connections, and use a third party API to gather geographic information related to where the failed attack came from.

These live RDP Brute Force attacks can come from all over the world, and this PS script will look at where these attacks are coming form, and plot the locations on an map in Azure Sentinel.
