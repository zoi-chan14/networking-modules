
# Technologies and Designs that power Private Networks

🔹 1. IP Addressing (foundation)
    • har device ko ek unique IP milta hai 
    • private network me usually range hoti hai: 
        ○ 192.168.x.x 
        ○ 10.x.x.x 
👉 bina IP ke bina koi communication hi nahi

🔹 2. DHCP (dynamic host configuration protocol ) 

    

    • automatic IP assign karta hai 
    • bina iske har device manually set karna padega 
👉 basically: “network ko alive rakhta hai”

🔹 3. ARP ( address resolution protocol ) 
    • IP → MAC mapping karta hai 
    • devices actually MAC pe baat karte hain 
👉 ye ensure karta hai ki data sahi device tak pahoche

    

🔹 4. Router / Gateway
    • network ka “brain” 🧠 
    • decide karta hai: 
        ○ data kaha bhejna hai 
        ○ internet access dena 
👉 bina router ke network isolated ho jata

🔹 5. Switch
    • devices ko aapas me connect karta hai 
    • fast internal communication deta hai 
👉 LAN ka backbone

🔹 6. DNS
    • domain name → IP me convert karta hai 
    • (google.com → IP) 
👉 warna tujhe har site ka IP yaad rakhna padta 😵

🔹 7. NAT (Network Address Translation)
    • private IP ko public IP me convert karta hai 
    • ek hi internet connection pe multiple devices chalne deta 

🔥 Final simple line:
👉 Private network = IP + DHCP + ARP + Router + Switch + DNS + NAT
