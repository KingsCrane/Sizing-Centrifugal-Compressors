# Sizing Centrifugal Compressors

The spreadsheet here is to size a centrifugal compressor and predict a real machine performance beforehand. Hence working with spreadsheets to bind gas dynamic data could be frustrating regarding iterations, following heads-ups could become handy:

__1.  Keep calm and do iteration!__

The first piece of puzzle is discharge temperature (T2). To calculate T2, you need to know some gas properties that are correlated to the gas temperature. Let’s read it again, you need gas properties to calculate temperature and you need that temperature for gas properties. Now what!

![](/README/1.jpg)

Firstly, you may apply suction side gas properties and calculate adiabatic discharge temperature. Then by this temperature, calculate compressibility (Z) and then, you will have polytropic temperature. It’s time for iteration! Now repeat all steps for new polytropic temperature and keep going until you realize that calculated polytropic temperature is almost constant. (Normally it gets to the right temperature with 3 or 4 iteration)

__2.  Experience is the key to success!__

Calculating discharge temperature, polytropic head, power consumption, and number of process stages are all quite straight forward. But, regarding compressor’s speed, number of impellers, and impeller diameter, you should be more careful. By the calculation sheet, you are free to change those parameters and see how other ones change, but always there are some limits!

![](/README/2.jpg)

In the excel sheet, there are already some factors available (flow coefficient, head coefficient, tip speed, specific speed, and Mach number) that might help you to keep changes into your control. However, I believe approved experiences could be a great asset here to broaden your horizons. If you have a vendor design available, check it for fun and see how close your estimation goes.

![](/README/3.jpg)

__3.  Breaking News!__

The bad news is that you have to do all calculation separately for each process stage. But be positive! This is a good opportunity to study more about centrifugal compressors. All references are available by one click.

![](/README/4.jpg)

__4.  CAUTION! MACROs are running all around__

The excel sheet is running some MACROs to keep the calculations working and for reducing legwork. I give my word that they are totally harmless. So, please enable the MACROs in your excel.

![](/README/5.jpg)

__5.  APOLOGY! To full-access freaks! ;)__

I am really sorry that everything is password protected. There’s nothing secret in the file. All formulas and equations are available at the right panel. There are many connected formulas in the spread sheet and passwords are only protecting the unity against unwanted changes. However, you may feel cheerful to know that unlocking and hacking into a protected excel file is not too easy! :)

__6.  Adobe PDF__

There are 14 PDF documents merged into the calculation sheet. To open them, it is only possible by having Adobe PDF reader installed on your computer (it does not work with other software like Foxit Reader). I’m sorry for that, but it is Microsoft problem :) if you insert a file into Excel when your default reader is “X”, later you can open it again only if you have “X” installed. However, you may [download free version of Adobe PDF from here!](https://acrobat.adobe.com/us/en/acrobat/pdf-reader.html)

__7.  Recommendation!__

Office documents with files inserted into them are prone to corruption. You may keep a fresh copy of the spread sheet for emergencies ;)

![]
