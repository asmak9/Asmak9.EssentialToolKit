# Asmak9.EssentialToolKit Library
**Asmak9.EssentialToolKit** is a 30 days free trial library that provides **UtilityKit**, **FileManagerKit** and **DateTimeFormats**  classes. **UtilityKit** class contains many commonly utilize methods, **FileManager** class contains many commonly utilize I/O operation methods and **DateTimeFormats** class provides many pre-defined Date/Time format values for quick/easy development. The **TrialExpirationInfo** class will provide detail information about this library's trial period expiration. You can install this library via Nuget package and enjoy 30 days free trial. You can use this library into your any **.NET 4.8 or above framework supported** projects.

### Nuget Installation Version 1.1.4: https://www.nuget.org/packages/Asmak9.EssentialToolKit/

### [Buy License Key](https://bit.ly/3mzMQsU) Copyright (c) [Asma's Blog](https://www.asmak9.com/)

# Basic Usage for TrialExpirationInfo class

```C#

using Asmak9.EssentialToolKit;

// Initialization (For 30 Days free Trial).
TrialExpirationInfo trialExpireInfo = new TrialExpirationInfo();

// Initialization (After Purchasing License Key).
string licenseKey = "YOUR_LICENSE_KEY";
TrialExpirationInfo trialExpireInfo = new TrialExpirationInfo(licenseKey);

// To Get Trial Expiration Date.
string trialExpireDate = trialExpireInfo.TrialExpireDate;

// To Get Trial Expiration Time.
string trialExpireTime = trialExpireInfo.TrialExpireTime;

// To Get Total Remaining Trial Expiration Days.
string trialExpireTime = trialExpireInfo.TotalRemainingTrialExpireDays;

// To Get Trial Expiration Detail Message.
string trialExpireTime = trialExpireInfo.TrialExpirationDetail;

```

# Basic Usage for UtilityKit class

```C#

using Asmak9.EssentialToolKit;

// Initialization (For 30 Days free Trial).
UtilityKit utilityKit = new UtilityKit();

// Initialization (After Purchasing License Key).
string licenseKey = "YOUR_LICENSE_KEY";
UtilityKit utilityKit = new UtilityKit(licenseKey);

// To Access Method (Methods utilization detail is avilable in documentation with sample code).
utilityKit.MethodName(...);

```

# Basic Usage for FileManagerKit class

```C#

using Asmak9.EssentialToolKit;

// Initialization (For 30 Days free Trial).
FileManagerKit fileManagerKit = new FileManagerKit();

// Initialization (After Purchasing License Key).
string licenseKey = "YOUR_LICENSE_KEY";
FileManagerKit fileManagerKit = new FileManagerKit(licenseKey);

// To Access Method (Methods utilization detail is avilable in documentation with sample code).
fileManagerKit.MethodName(...);

```

# Basic Usage for DateTimeFormats class

```C#

using Asmak9.EssentialToolKit;

// Initialization (For 30 Days free Trial).
DateTimeFormats datetimeFormats = new DateTimeFormatst();

// Initialization (After Purchasing License Key).
string licenseKey = "YOUR_LICENSE_KEY";
DateTimeFormats datetimeFormats = new DateTimeFormats(licenseKey);

// To Access Date/Time Formats (Format Properties utilization detail is avilable in documentation with sample code).
datetimeFormats.FormatProperty;

```

# TrialExpirationInfo class Documentation

1. [Library Trial Expiration Information](https://bit.ly/3iwLrQO)

# UtilityKit class Methods Documentation

1. [Build Web Url Query Params Method](https://bit.ly/3jIYAaE)
2. [Contains MAC Address of the System Method](https://bit.ly/36ADho1)
3. [Convert Base64 to BitmapImage Method](https://bit.ly/2GlixGs)
4. [Convert Bitmap to BitmapImage Method](https://bit.ly/3jLCPHh)
5. [Convert Bitmap to Bytes Method](https://bit.ly/3def9cj)
6. [Convert Bytes to Bitmap Method](https://bit.ly/34RDAsp)
7. [Convert Bytes to BitmapImage Method](https://bit.ly/2Ip168B)
8. [Convert Date/Time to String Method](https://bit.ly/313Cl8m)
9. [Convert Date/Time to Time Span Method](https://bit.ly/3lIvAAO)
10. [Convert List to Datatables Method](https://bit.ly/2ItRtFy)
11. [Convert List to String Method](https://bit.ly/3m09vhh)
12. [Convert List to String Array inside List Method](https://bit.ly/36CZNvH)
13. [Convert Number to Comma Separated Notation Method](https://bit.ly/3eePZuG)
14. [Convert Text to BitmapImage Method](https://bit.ly/327Vvdt)
15. [Convert TimeSpan to DateTime Method](https://bit.ly/2I8j3sf)
16. [Decode Bytes From Base64 Method](https://bit.ly/2Ubpyg7)
17. [Decode String From Base64 Method](https://bit.ly/38wxu3Z)
18. [Encode Content to Base64 Method](https://bit.ly/3lqxR3D)
19. [Get All MAC Addresses of the System Method](https://bit.ly/2IvghNw)
20. [Get App Assembly Version Method](https://bit.ly/2K4urWs)
21. [Get App Configuration Settings Method](https://bit.ly/36TvQag)
22. [Get App File Version Method](https://bit.ly/3pZtHCA)
23. [Get Time Duration Method](https://bit.ly/3m9qtKv)
24. [Get Total Days Method](https://bit.ly/2KBCytQ)
25. [Get Total Months Method](https://bit.ly/3fIOGET)
26. [Get Total Years Method](https://bit.ly/3fEgZV2)
27. [Internet Status Method](https://bit.ly/33lSWoQ)
28. [Is Time AM Method](https://bit.ly/36b4YTR)

# FileManagerKit class Methods Documentation (Coming Soon)

1. [Convert File Image to Bytes Method](https://bit.ly/3ngwxRQ)
2. [Copy File Method](https://bit.ly/37rtyR3)
3. [Copy Folder Method](https://bit.ly/3rbzWnz)
4. [Create File Method](https://bit.ly/3pcATKc) 
5. [Create Folder Method](https://bit.ly/3hoouA9)
6. [Export CSV File Method](https://bit.ly/2Jx9NP2)
7. [Get AppData Local Folder/File Full Path Method](https://bit.ly/3qajEtu)
8. [Get AppData Local Temp Folder Full Path Method](https://bit.ly/2LUljFo)
9. [Get AppData Roaming Folder Full Path Method](https://bit.ly/3a34tw3) 
10. [Get Desktop Folder Full Path Method](https://bit.ly/3iWTlVp)
11. [Get MyDocument Folder Full Path](https://bit.ly/305BLG0)
12. [Get Project (Visual Studio) Folder Full Path Method](https://bit.ly/3uRRsPA)
13. Get Random File Name Method
14. Get Windows Folder Full Path Method
15. Get Windows Program File Folder Full Path Method
16. Get Windows Program File X86 Folder Full Path Method
17. Import CSV File Method
18. Move File Method
19. Move Folder Method
20. Remove File Method
21. Remove Folder Method
22. UnZip Folder Method
23. Write Base64 to File Method
24. Write Binary Content to File Method
25. Write Content to File Method
26. Zip Folder Method

# DateTimeFormats class Pre-Defined Formats

1. [DateTime Formats usage Documentation](https://bit.ly/377sSAb)

```C#
/*

Default Date Format:            2020-10-01
Date Format-1:                  Thu, 01-Oct-2020
Date Format-2:                  Thursday, 01-Oct-2020
Date Format-3:                  01 October, 2020
Date Format-4:                  01-Oct-2020
Date Format-5:                  Thu, 01 October, 2020
Date Format-6:                  Thursday, 01 October, 2020

Default Time Format:            12:58:03.198
Time Format-1:                  12:58:03
Time Format-2:                  12:58:03 PM
Time Format-3:                  12:58 PM
Time Format-4:                  12:58:03.198 PM
Time Format-5:                  12:58

Default DateTime Format:       2020-10-01 12:58:03.198
DateTime Format-1:             01-Oct-2020 12:58:03 PM
DateTime Format-2:             Thursday, 01-Oct-2020 12:58:03 PM
DateTime Format-3:             Thu, 01-Oct-2020 12:58:03 PM
DateTime Format-4:             Thursday, 01-10-2020 12:58:03
DateTime Format-5:             Thu, 01-10-2020 12:58:03
DateTime Format-6:             Thu, 01 October, 2020 12:58:03
DateTime Format-7:             01 October, 2020 12:58:03 PM
DateTime Format-8:             Thu, 01 October, 2020 12:58 PM
DateTime Format-9:             Thursday, 01 October, 2020 12:58:03 PM
DateTime Format-10:            Thursday, 01 October, 2020 12:58:03
DateTime Format-11:            01-Oct-2020 12:58:03
DateTime Format-12:            01 October, 2020 12:58:03

*/

```

<br/>
<br/>
<br/>


Like, Share, Support, Subscribe!!!

#### YouTube: https://bit.ly/2sY1aBb 

#### Website: https://www.asmak9.com/

#### E-Store Bytezaar: https://www.bytezaar.com/

#### Facebook: https://www.facebook.com/AK.asmak9/

#### LinkedIn: https://www.linkedin.com/company/asmak9

#### Twitter: https://twitter.com/asmak/
