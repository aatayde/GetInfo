# GetInfo

## Get Physical Memory in Windows

> What if you wanted to upgrade your memory but didn't want to take your computer apart to find out what kind of memory you have?

`Get-CimInstance Win32_PhysicalMemory | Select-Object BankLabel, Capacity, DeviceLocator, Manufacturer, PartNumber, Speed1`

![memory information](./Screenshot%202025-03-11%20at%2010.05.06 PM.png)
