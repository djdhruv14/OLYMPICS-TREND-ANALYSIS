I analyzed 120 years of Olympic data.

Tools Used:
Snowflake SQL (raw data → insights)
Streamlit (interactive dashboards)
Plotly (visual storytelling)

INSIGHTS: 
1. 20-Year Olympians: Precision Sports' Edge
Sports like Shooting and Equestrian have athletes competing for 20+ years (Shooting
average: 12 years!).
Career span measures years between an athlete’s first/last Olympics.

2. Olympic Dynasties: When One Nation Owns the Sport
In Basketball, the USA owns 50% of all medals. But in Hockey? India leads with 60% an absolute dynasty!
Dominance % = (Country’s medals / Sport’s total medals).

3. Age Wins Medals Differently
Athletes in precision sports (Shooting, Archery) peak 10+ years later than gymnasts. Experience > youth when accuracy matters!

Gymnastics: 19-year-olds dominate (Young quartile)

Equestrian: 40+ is prime (Veteran quartile)
Quartiles = age brackets splitting athletes into 4 groups

4.  Global Power Shifts
Using DENSE_RANK (a tie-friendly ranking system), I tracked medal leaders yearly:

2000: USA > RUSSIA > CHINA

2020: USA >CHINA > JAPAN

The United States leads in roughly two-thirds of all the Games, especially in the initial period (1896–1936) and again post-Cold War (1992–2016). Between 1952–1988, the Soviet Union made a solid challenge, standing at the top in six successive Olympiads.



