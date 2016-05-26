# Bhagavat Gita verses for fortune

# HOWTO: set up custom fortune cookies files
1. git clone git@github.com:ybudimirov/fortune-bg.git
2. cd fortune-bg
3. chmod 644 bg*
4. chown root.root bg*
5. cp -rp bg* /usr/share/games/fortunes/
6. /usr/games/fortune bg
7. echo "/usr/games/fortune bg" >> ~/.bashrc
7. OPTIONAL if there is issue with fonts, install ttf-indic-fonts

# HOWTO: create custom fortune cookies files
1. Open editor and add the strings that you want to be shown when running "fortune" in terminal. 
BE SURE to add a single line with a letter % in it, between every string.
2. Save this file to whatever file name you want; this guide uses "yourlist" as example.
3. When done adding strings, run the command "strfile -c % yourlist yourlist.dat". 
This will create a .dat file for your cookie file, which contains a header structure and a table of file offsets for each group of lines. This allows random access of the strings.
4. Run "fortune yourlist" to eat the fruit of your work. That's it! 
5. If you want this cookie file to appear as any other of the standard fortune cookies (when simply running "fortune"), just add your string file and .dat file into "/usr/share/games/fortunes/".
6. Oh, and one more thing: if you want to change anything in "yourfile", you will need to repeat this HOWTO again for it to work.

# Usage example:

Б.Г. 11_39
    
    वायुर्यमोऽग्निर्वरुणः शशाङ्कः
            प्रजापतिस्त्वं प्रपितामहश्च ।
    नमो नमस्तेऽस्तु सहस्रकृत्वः
            पुनश्च भूयोऽपि नमो नमस्ते ॥ ११-३९॥
    
    вайур йамо 'гнир варунах шашанках 
    праджапатис твам прапитамахаш ча 
    намо намас те 'сту сахасра-критвах 
    пунаш ча бхуйо 'пи намо намас те 
    
    вайух - воздух; йамах - правитель; агних - огонь; варунах - вода; шаша-анках - луна; праджапатих - Брахма; твам - Ты; 
    прапитамахах - прадед; ча - также; намах - поклон; намах - поклон; те - Тебе; асту - да будет; сахасра-критвах - тысячу раз; 
    пунах ча - и еще; бхуйах - снова; апи - также; намах - поклон; намах те - почтительный поклон Тебе.
    
    Ты и воздух, и верховный повелитель! Ты - огонь и вода, и луна! Ты - Брахма, первый обитатель мира, 
    и Ты - прародитель всего сущего. Поэтому я тысячу раз склоняюсь перед Тобой, снова и снова, и так без конца!
