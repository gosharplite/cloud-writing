# 紮實的 DroiBaaS 後台
作者：徐德平，上海卓易科技台北研究院，2017年1月
<hr>
DroiBaaS 為了在雲端立足，建構於四層清楚的架構上 - 硬體層、作業系統層、容器群集層、應用層。其中的關鍵是容器群集層，因為在雲端海量的壓力下，系統必須用新技術來實現。這一層用到的新技術，也直接影響其他層級的設計。在兩年的激烈競爭下，開源項目 Kubernetes 脫穎而出，成為管理容器群集的首選。卓易雲端從兩年前就跟上這個技術，用 K8S 來管理數以千計的 Docker 容器。
<br><br>
強大的容器管理系統，要有堅固的作業系統支持。CoreOS 這幾年不斷創新並領導雲端技術的走向，因此成為卓易雲端選用的作業系統層。在效率和精簡層級的考量下，我們捨棄 VM 而直接把容器散佈在實體機上。因為有 CoreOS 和 K8S 高效的分散式設計，實體機上的容器得以發揮出比用 VM 高出數倍的資源運用。
<br><br>
硬體網路層則要走向能自動化的 SDN 架構，卓易雲端選用 Calico 網路讓量多且變化頻繁的容器穩定的互通。生存於容器中的應用也有關鍵變化，專門為雲端新世界所設計的 Go 語言被大量的使用，讓應用服務能在分散式的環境下達到 Cloud Native 的理想。HTTP/1.1 稱霸網路二十年後，HTTP/2 誕生了。新的通訊協議在資料壓縮和多路複用技術上有長足的進步，卓易雲端選用 gRPC 來取得 HTTP/2 的好處，用於服務之間資料的高效傳輸。
<br><br>
有了容器和管理它們的分散式系統，卓易雲端打造全自動的 CI/CD 系統，除了免除人為的佈署錯誤，更是為了實行微服務的理念。這一切讓我們擁有走向雲端的要素 - 容器、管理系統、微服務。而走上雲端的優勢則是能組織分散的小型開發團隊，在良好的授權環境下，讓工程師能極致的發揮出創造力。