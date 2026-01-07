# sandwich-conductor
  
在遵守物理定律的情況下 利用結構 是否能夠做到接近超導體的效果?     
本文 核心主旨為 在非超導體情況下 能否以結構做到接近超導體特性為主旨 並非做到1比1超導體之功能      
1.0所假設材料 石墨 氣體氙 矽油 為範例的組合結構 石墨為核心 xe為縫隙夾層 矽油為穩定      
(不用一定要這些材料 只要能找到同樣成立的材料就好 此為單純展示範例結構 力求最便宜材料 最爛的效果 結構可行性以可成立的最小可行性為標準)       
在結構假設是在常溫下的奈米尺寸構造 此結構成立之可能性以 1.凡德瓦力力 2.鏡像勢能態 3.拉普拉斯壓力 成立 工程上要抽真空    
A. 氣體氙（Xe）為什麼可以在石墨界面附近存在而不立即消散？       
物理機制：波紋輔助吸附 (Ripple-assisted adsorption) 形成深層位能阱      
參考文獻：Ripple-assisted adsorption of noble gases on graphene at room temperature (2025).     
網址：https://doi.org/10.1093/nsr/nwaf506        
補充:必須在奈米尺寸下 巨觀下此結構不成立  
B. 為什麼界面附近允許電子存在低能束縛狀態？   
物理機制：鏡像勢能態 (Image Potential States, IPS) 與 Xe 介電屏蔽效應   
參考文獻：Electronic states in thin Xe films on metal surfaces   
網址：https://doi.org/10.1103/PhysRevB.48.11361   
C. 為什麼 Xe 不會從奈米結構中立即外洩？   
物理機制：奈米狹縫幾何限制 (Geometric Confinement) 與拉普拉斯壓力  
參考文獻：Surface nanobubbles and nanodroplets 跟 Phase separation in confined systems  
網址：https://doi.org/10.1103/RevModPhys.87.981  
https://iopscience.iop.org/article/10.1088/0034-4885/62/12/201  
極平滑怎麼做到的   
1.結構穩定性  
參考文獻: Surface nanobubbles and nanodroplets   
(網址: https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.87.981)  
2. 平滑度  
參考文獻: Ripple-assisted adsorption and crystallization of noble gases on graphene (2025)   
網址: https://doi.org/10.1093/nsr/nwaf506  
由兩篇文獻可知道Xe原子會被石墨的褶皺死死鎖住 Xe也不是亂跑的氣體而是在石墨表面整齊排列 做到了物理上的自然平滑度 也保證了穩定性   
3.低阻力  
參考文獻: Electron Interactions with Xenon, Journal of Physical and Chemical Reference Data (JPCRD).  
https://jpcrd.nist.gov/  
你可以直接google NIST Xenon electron scattering cross section 0.65 eV 下載pdf查證   
在奈米尺度下 電子是波 這對其他導體都是巨大威脅 因為會造成紊亂散射 那為捨麼我們能降低阻力呢?   
靠拉姆紹爾-湯森效應(Ramsauer-Townsend Effect)  
波的穿透： 當電子波靠近Xe原子時 它會感受到原子的吸引力而加速  
相位相消： 當電子的能量剛好是 0.65eV時 電子波在原子內外的起伏會產生相消干涉  
一般阻力區 10eV散射截面數值是24.5  
透明視窗區 0.65eV數值暴跌到0.126  
24.5/0.126=194.444....  
4.電子為捨麼只會在固體表面跑?  
這是經典的maxwell邊界條件理論 在導體石墨與低介電常數質Xe的界面 所有的自由電荷必須分布在表面  
你如果還要我找文獻建議去找maxwell  

至此我們如果假設上述皆成立 我們就成功地建造了一個 室溫下彈道傳輸導體  如果之後實驗有誤 別找我 找他們 我只是利用現有物理提出假說 我沒違反任何物理   

如何失敗?   
我認為如何失敗 比我上面說的怎麼成功都還更重要   
以結構的最小可行性 矽油50nm Xe 2.5nm 石墨 2nm 0.65ev  以下你們可以自己驗算 因為我不會做pdf 我只會打文字檔 我相信你們會算 不需要我  
在尺寸寸下 有三種最大死法  
1.量子穿隧  
你們可以自己驗算 我算了3次左右 大概在0.00005左右 1/20000  
2.聲子散射  
不管是任何物體 都無法在常溫下避免聲子散射 所以此結構最小bme必死 但是足夠測試  
3.工程坍塌  
16.8MPa的拉普拉斯壓力會試圖壓扁脆弱的結構  
理論上最小bme很難成立 但是是工程問題 不是假說問題 你們想成立簡單點可以換尺寸 自己成立 但是同樣 只有nm尺寸可成立 巨觀100%不成立  
接下來是可能會遇到的小死法  
1.原子級雜質 2.電壓雜訊 3.矽油的分層浸潤  
工程問題 我是假說  
4.空間電荷效應  
不會死 但是會降低效率   
也可能還有其他的問題 我目前也不知道 畢竟這只是假說 需要實驗才能知道全部問題   

以上是最小bme 你們可以自己改變結構所使用的材料 跟尺寸 來保證穩定性 跟使用時間   
現在可以說我認為你們為捨麼值得測試的優點了 上述的穩定性你們都能自己算自己改 我只是提供一個最爛最爛的樣子 給大家看   
現在最好的半導體 我所知道的 不考慮cpo因為我不知道cpo多強   
目前地表最強的半導體工藝台積電2nmGAAFET    
傳輸距離 10-40m 1.0最小可能性為560nm左右    
電阻來源 晶格散射 1.0:量子接觸電阻   
散熱瓶頸 極高 1.0:極低電子不與原子交換能量理論上不發熱 但是需實驗 無法保證 且工程必有缺陷 不能完美 
我認為上述條件跟成本 這是一場 幾乎沒有損失的賭局 你們只要肯賭就能有答案 反正也沒損失比起幾10億美金 驗算跟看完文章可能都不需要10分鐘  
材料都是可以換得 但是目前我找不到 足夠的文獻來替我背書跟引用 反正這是免費的開源  
A2 我目前想的到的 有幾個 或許能用 如雲母 白石墨 加固可使用SAM   
我不保證有用 我只提出假說   

