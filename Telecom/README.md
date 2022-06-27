# Telecom Project
**The goal**:
- Find out which tariff is more profitable: "Smart" or "Ultra"

**Input data**: 
- Sample of 500 users' data points: who they are, where from, what tariff use, how many messages send and how much traffic use

**Tariffs description**  

*Smart*
- Price: 550 rub
- Includes 500 min, 50 messages, 15GB traffic
- Above this:
    - 3 rub/min
    - 3 rub/message
    - 200 rub/GB
  
*Ultra*
- Price: 1950 rub
- Includes 3000 min, 1000 messages, 30GB traffic
- Above this:
    - 1 rub/min
    - 1 rub/message
    - 150 rub/GB

**Important note**  
- Seconds are always rounded to minutes
- Megabytes are always rounded to gigabytes
- Traffic is summed for one month
- Unused minutes, messages, and traffic can not be shifted to new month

**Analysis structure**:
* Data overview
* Data preparation
* Data analysis
* Hypothesis testing
* Results
