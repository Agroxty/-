![8.png](https://raw.githubusercontent.com/mapleasun/-/main/8.png)

# 多元化5G專網應用
## 組員:曾彥齊、王信憲、戴維德、宋俊憲、楊辰鳴
#### 網路通訊分為兩種類型：一是消費者使用的公眾網路，二是用於特殊任務的專用網路，例如交通、電力和軍事等領域;然而，近年來隨著5G技術的演進，我們可以透過網路切片技術和專網專用頻譜等解決方案來打造5G專網，這促使智慧城市、智慧醫療、智慧工廠等領域展現出無限可能，滿足各自對於專屬5G專網的需求。5G專網可應用於多個行業，包括製造業、物流和運輸業、能源業、農業、醫療保健等，這些行業對於低延遲、高頻寬和可靠連接的需求推動了5G專網的快速發展。
### EMS產業供應鏈安排不易，且客戶對於高精度、微型化的客製化產品規格需求，形成電子電機產業其「少量多樣」的訂單特性，未來可在部署前述5G應用後，透過5G產線彈性調整創新應用，來提升管理效率與降低生產成本，實現產線彈性調整。電子電機製造業針對5G應用需求主要包含以下幾個方面：
#### 工業自動化和智能化：5G的低延遲和高可靠性可以實現生產線的即時監控和控制，使整個製造過程更加智能化和自動化。同時，5G還可以實現生產線之間的智能協作，提高生產效率和產品質量。
#### 數據應用和分析整合：製造過程中產生的數據量非常多樣，包括生產過程中的傳感器數據、機器人操作數據、產品質量數據等等。5G的高速傳輸和低延遲可以實現實時的數據收集和傳輸，使得製造企業可以更好地應用數據進行生產和運營管理。
#### 增強現場人員的支援：5G的高速傳輸和低延遲可以支援現場工人使用智能眼鏡、無線手持設備等工具，提供即時信息和操作指導，使得現場人員的生產效率和質量更加高效和穩定。
#### 物聯網應用：製造業的物聯網應用需要高速的傳輸和低延遲的連接，才能夠實現智能感知、智能識別和智能控制。5G的高速傳輸和低延遲可以支援大量的物聯網設備和應用，實現智能化和自動化的生產。

### 5G沉浸式光影交響首部曲
<a href="https://www.youtube.com/watch?v=FmdRDOcdUrc&list=PPSV" target="_blank"><img src="https://raw.githubusercontent.com/mapleasun/-/main/%E6%93%B7%E5%8F%96.PNG"
alt="5G沉浸式光影交響首部曲" width="400" height="250" border="10" /></a>
---------------------------------------------

### 5G專網兩大關鍵架構

大多數人應該都聽過5G可帶來的功能性提升，從應用層面來看，增強型行動寬頻通訊(eMBB)提供超高速的直播串流及擴增實境/虛擬實境(AR/VR)體驗；超可靠低延遲通訊(uRLLC)支援關鍵性的任務應用、自動駕駛或製造業自動化；大規模機器類型通訊(mMTC)則實現物聯網和智慧城市部署所需的大量設備連結。然而，讓5G技術受到專網青睞的主因在於其核心設計，在5G的架構導入兩個重要概念讓5G網路在應用上更有彈性，分別為：

．服務化架構(Service Based Architecture, SBA)

．控制和使用者平面分離(Control and User Plane Separation, CUPS)

### 服務化架構(SBA)

服務化架構廣泛地用於軟體設計來提升系統模組化程度。這樣的架構將系統功能拆解成個別的功能模組，並透過標準的應用程式介面(API)相互溝通。第三代合作夥伴計畫(3GPP)將行動網路服務重整為數個獨立的服務並取名為網路功能(Network Function, NF)。每個網路功能負責一項特定的工作並透過服務化介面(Service Based Interface, SBI)與其它網路功能進行溝通(圖1)。
![1.png](https://raw.githubusercontent.com/mapleasun/-/main/1.png)
網路功能的相互協作建構起整個5G的運作系統，像是帳戶驗證、IP位址分配、策略控制，以及使用者資料管理。服務化架構讓5G系統變得非常有彈性，更容易整合新的服務和應用來滿足不同產業的需求。

### 控制和使用者平面分離(CUPS)

5G架構依照控制平面(Control Plane)和使用者平面(User Plane)分離所設計，電信業者可以將5G的控制跟資料轉送功能分開部署，控制平面可置於中央機房，而使用者平面功能(User Plane Function, UPF)可以因應不同場域的資料處理需求而擺放於不同位置(圖2)。
![2.png](https://raw.githubusercontent.com/mapleasun/-/main/2.png)
服務化架構與控制和使用者平面分離為行動網路規畫提供絕佳彈性，也可以讓多存取邊緣運算(Multi-access Edge Computing, MEC)和5G網路的整合更加容易。邊緣運算服務可以透過服務化架構使用5G核心網路資源，並視需求部署於合適的位置，再由使用者平面功能協助將資料導至指定的運算資源。

了解5G網路為什麼適合專網應用後，接著來看一下不同5G專網的部署情境。

### 獨立5G專網架構
### 5G專網分三種部屬方式
按照與電信業者整合程度多寡，由低到高分為以下三類：

在獨立專網架構下，整個網路皆由企業用戶建置和運轉，以此確保對網路具有完全的管控權。由於此類網路完全獨立於公用網路之外，可減少資料外洩的風險(圖3)。主要的缺點是建置與運轉此類網路須投入相當高的經費，並且須聘僱具備電信專業知識的技術人員協助進行網路維運。
![3.png](https://raw.githubusercontent.com/mapleasun/-/main/3.png)
雖然成本高昂，獨立5G專網依舊非常適合用於擁有大量資源以及對資安高度重視的公共安全機構和大型企業。舉例來說，當緊急事件發生時，可使用獨立運行的車載5G系統來為救援團隊提供緊急通訊網路。

### 共享5G專網架構

共享5G專網架構藉由跟電信業者的公用網路共享網路設施來降低5G專網的建置成本。依照不同的商業需求，使用者可以決定哪些元件自行管理，哪些交由電信業者進行管理(圖4)。
對於智慧工廠應用來說，將邊緣運算(MEC)和使用者平面(UPF)留在工廠裡面或許是比較好的選擇，如此可以確保網路滿足低延遲的要求並且保有自行擴充功能的彈性。
其他像是體育場或展覽館等應用場景，高速及穩定連線為其主要訴求，企業可以自行建置基地台等設備以確保網路品質和覆蓋程度都在控制範圍內，而網路系統的管理及運轉就交由電信業者來處理。
![4.png](https://raw.githubusercontent.com/mapleasun/-/main/4.png)
### 網路切片5G專網架構

使用網路切片可以在電信業者既有的公用網路設施上建立私有的端到端連線，並確保每個連線皆擁有獨立頻寬不互相干擾。採用這種方式的專網建置成本雖然與其他架構相比最低，但可操控性同樣也是最低的(圖5)。
![5.png](https://raw.githubusercontent.com/mapleasun/-/main/5.png)
網路切片5G專網架構適合大範圍的布建場景，像是智慧城市物聯網或自駕車的服務。不同組織可以向電信業者租賃專有的頻寬，再依照商業類型選擇不同的服務級別協定(SLA)以滿足其需求。

### 資安

保護公司敏感資料不外流需要借助各種層面的保護機制，可以透過導入軟體層面的網際網路安全協定(IPsec)或是硬體層面的媒體存取控制安全標準(MACsec)加密功能來實現。

功能性跟延展性

有鑑於5G專網可應用於各種不同場域，傳輸網路必須能讓5G網路發揮最大效能。因此，傳輸網路設備應該具有足夠的資料緩衝區、服務品質(QoS)的功能，並具備多樣的網路接口來連接各式無線存取設備。

5G專網將會是5G技術最重要的應用之一，各國政府及產業領導者紛紛投入研究以發掘商機，而傳輸網路位於系統中心，串連起所有設備，扮演網路骨幹的角色。在此趨勢下，各個設備商皆推出相對應的產品，如優達科技S9500系列開放式存取交換器，為各式應用規畫

不同規格，以滿足5G專網多樣化的需求。
---------------------------------------------
![15.jpg](https://github.com/C109252210/-/blob/05ca63fa203b68a385d5238475572f23193b0919/15.jpg)

### 5G將改變未來戰爭面貌
5G技術不但有廣泛的民用前景，也具備相當大的軍事潛力，是一種足以改變未來戰爭面貌的科學技術。5G作為第五代移動通信技術，具有高速率、大容量、高可靠、低時延、低功耗等特性，一旦應用於軍事領域，可大幅提升信息網絡互聯互通性能，增強數據傳輸處理效率，提高指揮控制能力，還可充分釋放虛擬現實、大數據、雲計算、人工智能、軍事物聯網等顛覆性技術的戰爭潛能，加速智能化戰爭演變進程。5G應用較高的通信頻段，數據傳輸速率得到大幅提升，其峰值速率是當前4G的20倍，不但可提高戰場各類數據的傳輸速率，還能提高指揮效率。5G技術可同時為每平方公裡百萬量級的終端提供互聯服務，相比4G千餘台的設備連接容量，能力大幅躍升。5G技術傳輸延遲顯著降低，實現真正的秒傳，5G的超低延時特性，為時間敏感型和對傳輸可靠性要求高的軍事應用提供了可能，如智能平台自主交戰、無人系統遠程操控等，在進一步提高作戰精准化的同時，推動戰爭形態向智能化方向加速演變。美國一直高度重視5G的軍事應用，將其視為改變未來戰爭的關鍵技術之一。2018年，美國國際戰略研究中心將5G定義為新軍事能力的基礎技術。2019年，美國國會研究服務部指出5G 技術在自動駕駛、指揮控制以及情報、監視和偵察等領域具有巨大軍事應用潛力，還可以實現“蜂群”等新作戰概念。同月，美國國會武裝力量委員會提交的《2020財年授權法案》，強調要重視5G對未來作戰的支撐作用，要求國防部盡快制定一份將5G納入武器發展的戰略規劃，以推動軍方對該技術軍事應用的研究。 

5G改變未來戰爭面貌的場景有三個，第一，基於“5G+VR”的軍事訓練。虛擬現實系統是未來作戰人機交互和軍事訓練的重要手段，5G可大幅提升虛擬現實系統的實用性，高清畫面和交互信息可通過5G網絡實時傳輸至用戶，使受訓人員僅需穿戴頭盔和必要的武器裝備就能參與訓練，擺脫背負式計算設備、各種線纜和訓練場地的束縛，真正做到貼近實戰。第二，未來戰爭是體系與體系的對抗，隨著作戰空間/領域的擴展、無人系統比重的提高和智能武器裝備的增加，通過5G技術的海量設備物聯和異構網絡整合能力，可以形成“人+機+物”互聯互通的戰場物聯網。借助戰場物聯網，指揮員可對目標進行實時偵察、識別、跟蹤和預警，實現感知快、研判快、決策快、行動快，發現即摧毀將成為可能﹔還可實現對各作戰單元的高效組織、精准控制和及時調整，以及計劃外的自主協同，最大程度發揮體系作戰能力。第三，基於邊緣智能的無人作戰。極低時延下大量數據可靠傳輸是制約無人系統大規模作戰應用的重要因素，如果時延不能控制在幾毫秒以內，無人作戰系統在缺乏指令數據的控制下，很容易造成誤擊、失控等意外事故。5G技術高速率、低時延等特性，可保障人類對無人系統的可靠控制，並通過網絡切片和邊緣計算等技術推動無人系統的作戰應用。

### 5G專網應用總結
5G技術的到來為各行各業帶來了前所未有的變革和發展機遇。作為第五代移動通信技術，5G擁有高速率、大容量、高可靠、低延遲、低功耗等特性，能夠滿足不同應用場景的需求，特別是在智慧城市、製造業、農業和軍事等領域的應用，展現了強大的潛力和廣泛的應用前景。

從民用角度來看，5G技術以其高速傳輸、低延遲和大容量的特點，推動了智慧城市、智慧醫療、智慧交通等領域的發展。智慧城市利用5G的高速連接，實現了城市各個部門的互聯互通，提升了城市管理的效率和便利性；智慧醫療借助5G技術，實現了醫療數據的即時傳輸和醫療服務的個性化，提高了醫療資源的利用效率和醫療水平；智慧交通則通過5G技術實現了交通系統的智能化和高效化管理，提升了交通安全性和運輸效率。

從軍事領域來看，5G技術的應用為現代戰爭帶來了全新的變革。5G技術的高速率、大容量和低延遲特性，使得軍事通信更加高效和可靠。未來戰爭中，5G技術將成為戰場通信的核心，實現戰場上各種平台的無縫連接和信息共享，提升指揮控制效率和作戰效能。特別是在無人裝備和智能武器的應用方面，5G技術可以支持無人機和無人車的遠程操控和自主決策，提升作戰的靈活性和精確性，減少人員傷亡。

總體而言，5G專網技術為各行各業的數位化轉型和智能化升級提供了強有力的技術支持。智慧城市、製造業、農業和軍事等領域的應用展示了5G技術的廣泛前景和深遠影響。隨著5G技術的持續發展和普及，未來隨著5G技術的持續發展和普及，將有更多創新應用出現，進一步推動各行各業的數位化轉型和智能化升級，創造更多的社會和經濟價值。
