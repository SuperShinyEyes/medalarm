medalarm
========

Medalarm: Medicine alarm

Problem: I take medicine everyday but it’s hard to remember everyday even though I have alarm set on my cell phone – I might not be at home when the alarm rings. The other problem is I don’t always remember if I have already taken medicine or not which might be a bigger issue.

Functionality: RTC module keeps the time. LED tells whether I have taken medicine or not. Medalarm tracks maximum two days of medicine dose history. So it will still tell you to take medicine past midnight if you haven’t taken any the day before. It tells you when you took medicine last time. You can manually set time and it will be recorded to RTC. Though this manual time modification might cause some bugs which I couldn’t figure out why.

Limitation: I was lazy to implement year modification in time change mode. This may not be any big issue but it might mess up with Feb since once in four years Feb has 29 days.

Note: I used JeeLabs RTC DS1340, not the one in the layout image. You should DS3231 library which I edited, not the original one. In maximum I have used Medalarm for 30+hours. I don’t know how it will function in long run. If something happens please let me know.

I hope you find it useful and stay healthy :)