## Welcome to the TTU CWBT 👋

大同大學(TTU)無線寬頻技術中心(Center of Wireless Broadband Technology, CWBT)自2008年成立至今，長期致力於次世代行動通訊網路技術之研究，依領域概分為系統(System)、網路(Network)及AI應用(AI Applications)等三大組別，整合跨領域資源與專業知識，積極投入5G/6G行動通訊、物聯網(IoT)、邊緣運算及人工智慧於通訊系統或服務之創新應用等核心技術開發。中心亦與產業界緊密合作，參與多項研究計畫與技術轉移案，致力於培育具備理論與實務能力之通訊人才，推動臺灣在無線通訊領域的技術發展與國際競爭力。

## Webside
[Cho group](https://sites.google.com/view/lcho/home?authuser=0)


### Group of signal processing
訊號處理組致力於 **無線傳輸時使用的波型研究** ，研究重點涵蓋 **尋找OFDM (orhogonal frequency-division multiplexing)與其延伸波型的減少缺點與效能降低之平衡、衛星訊號的多天線接收技** 、以及**下世代行動通訊(6G)之使用技術** 。我們以理論推理與電腦實驗模擬為主，並輔以實際設備做實際測試。

#### 主要研究方向
##### OFDM的效能與缺點之平衡

- 主要減少其PAPR(peak-to-average power ratio)與非線性PA(power amplifier)所造成的訊號失真問題
    - 使用companding來放大能量小的訊號、縮小能量大的訊號降低PAPR
    - 使用PGIR(Papoulis-Gerchberg type iterative reconstruction)的訊號還原技術還原失真訊號
    - 使用Tone Reservation保留一部份的子載波，使其PAPR降低
- OFDM之延伸波型
    - OFDM-IM (index modulation)
    - DFT-s-OFDM (discrete Fourier transform-spread-OFDM)
    - Optical OFDM
##### 其他波型
- OTFS

##### 衛星訊號之多接收天線處理
- 使用了MRC(maximum ratio combining)、EGC(equal gain combining)合成多路接收訊號，放大其訊號能量，使其SNR(signal-to-noise ratio)變高
- 練續接收訊號的同時也連續合成訊號，達成不中斷訊號

##### 下世代行動通訊(6G)使用技術
- ISAC(integral sensing and communication)，能夠讓通訊擁有感測能力，或是在感測同時能夠傳輸訊息
- RIS(reconfigurable intelligent surface)，能夠反射mmWave，使其覆蓋範圍變得更廣

#### 我們的開發工具
通訊使用了大量的數學矩陣運算，因此會大量使用MATLAB作為軟體模擬。
而目前有以下實驗器材
- Yttek YTPC0564 (E1000 SDR)
- Yttek YTRS0289 (RIS)
- Yttek YTFE0285 (mmWave陣列天線模組)
- USRP B210


### Group of network

網路組致力於 **次世代網路技術研究與應用開發**，研究重點涵蓋 **O-RAN（Open Radio Access Network）架構設計與實作**、**核心網路（Core Network）環境建置**、以及 **行動通訊資訊安全（Cybersecurity）漏洞分析**。我們以系統實作與攻防實驗為核心，結合理論研究與實務應用。

#### 主要研究方向

##### O-RAN 技術與實驗平台建置
- 探討開放式 RAN 架構（包括 DU、CU、RU 分離）
- 建立模擬與實體 O-RAN 測試平台
- 整合 xApp / rApp 實驗環境，實作智慧化無線資源管理

##### 5G/6G standalone核心網路研究
- 核心網元（AMF、SMF、UPF 等）行為模擬與弱點測試
- 自建 Open5GS / Free5GC 測試環境

##### 通訊安全與漏洞分析
- 分析通訊協定中潛在的攻擊向量（如 AMF 註冊欺騙、DoS 攻擊）
- 探討資安防護機制於 O-RAN 與核心網中的整合方式
- 建立虛擬化與容器化環境下的安全測試平台

#### 我們的開發理念與平台

我們崇尚 **開源工具與自由軟體** 的精神，廣泛使用以下工具與平台進行系統建置與測試：

- GNU Radio
- Linux（Ubuntu-based & Arch-base 開發環境）

目前使用的開發板與實驗設備包括：

- USRP B210
- ZedBoard


### Group of AI

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
