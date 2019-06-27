specification:

i am using mac book pro. so i don't need to add any driver like chromDriver or Firefox Driver or sth like gecko driver.
So the only thing is just go to safari 
and click develop option and then click on alow remote automation(you can find it at the last of option).

but are using window oprating system. just do this one
       # WebDriver driver = new SafariDriver(); just delete this one and add codes provided below
       
       
        File gecko = new File("G:\\seleniumLab\\chromedriver.exe");
        System.setProperty("driver.gecko.driver", gecko.getAbsolutePath());
        WebDriver driver;
        driver = new ChromeDriver();
        
       # keep the other codes as it is


that's all.

Thanks for your download.
