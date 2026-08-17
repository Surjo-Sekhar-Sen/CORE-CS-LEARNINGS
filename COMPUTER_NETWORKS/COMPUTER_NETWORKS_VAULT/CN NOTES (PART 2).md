### Basic Characteristics of a Computer Network

![[Pasted image 20260817061402.png]]
#### 1. Fault Tolerance (Reliability)

- **Definition:** Network ki woh capability jisse woh failures ke bawajood kaam karta rahe.
    
- **Goal:** No loss of service. Agar ek rasta block ho jaye, toh network ko doosra rasta dhoondna chahiye.
    
- **Analogy:** Jaise college se ghar jaate waqt agar regular raasta band ho, toh hum naya raasta dhoondte hain. Waise hi, agar koi router ya link down ho jaye, toh data dusre path se travel karega.
    
![[Pasted image 20260817061550.png]]
#### 2. Scalability

- **Definition:** Network ki ability ki woh badhti hui needs ke saath growth kare bina performance giraye.
    
- **Example:** Internet is the best example. Roz karodo nayi devices add hoti hain, lekin internet ka speed aur performance maintain rehta hai.
    
- **Technical Note:** Agar 10 computers hain aur 10 aur add kar diye, toh system pe load nahi aana chahiye; it should scale gracefully.
    
![[Pasted image 20260817074906.png]]
#### 3. Quality of Service (QoS)

- **Definition:** Data traffic ko manage karna aur priority set karna taaki loss aur delay kam ho.
    
- **Why is it important?** Router ke paas ek saath multiple packets aa sakte hain (e.g., email aur voice call).
    
- **Priority Rules:**
    
    - **Real-time Data:** (e.g., VoIP(voice-over IP) calls/WhatsApp calls) — Inko **high priority** milti hai kyunki inme 1 second ka delay bhi bahut bura experience deta hai.
        
    - **Normal Data:** (e.g., Email) — Inhe lower priority di ja sakti hai kyunki agar email 1-2 second late bhi pohanche, toh fark nahi padta.
        
![[Pasted image 20260817075136.png]]

![[Pasted image 20260817075212.png]]
#### 4. Security

- **Definition:** Unauthorized access, misuse, ya forgery se network ko bachana.
    
- **CIA Triad (Important for Interviews):**
    
    - **Confidentiality:** Data sirf sender aur receiver hi samajh sake (Encryption).
        
    - **Integrity:** Data me koi modification na ho (Sender jo bheje, wahi receiver ko mile).
        
    - **Availability:** Resources hamesha access ke liye ready rahein (Attacker server ko down na kar sake).
        
![[Pasted image 20260817075255.png]]
### Interview Perspective (MAANG Focus)

- **QoS Questions:** Aksar pucha jata hai ki "Routers traffic prioritize kaise karte hain?" — Iska jawab QoS mechanisms (Queuing algorithms) hota hai. Yaad rakhna ki latency-sensitive apps (VoIP, Video Streaming) ko bandwidth/priority zyada milti hai.
    
- **Security Concept:** CIA triad pe command rakho. Security sirf password nahi hai; yeh end-to-end communication ki safety hai.
    
- **Scalability:** Systems design interviews me "How do you scale your backend/network?" waale sawaal isi foundation se nikalte hain.

## ==MORE QUESTIONS ABOUT NETWORK AND DATA CENTERS!!==

![[Pasted image 20260817082241.png]]

![[Pasted image 20260817082257.png]]

## ==WHY IS WIFI USUALLY STRONGER THAN MOBILE DATA??==
![[Pasted image 20260817082357.png]]

## ==FULL PROCESS OF DATA MOVEMENT IN BRIEF!!==
![[Pasted image 20260817082441.png]]

## ==ORIGIN AND EDGE SERVERS??==

![[Pasted image 20260817082734.png]]

![[Pasted image 20260817082830.png]]

![[Pasted image 20260817082900.png]]

## ==HOW DOES NETFLIX OR YOUTUBE SCALE TO MILLIONS OF USERS GLOBALLY WITHOUT CRASHING??==
![[Pasted image 20260817083028.png]]