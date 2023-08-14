Master Thesis Elham Aref
--------------------------------------------------

Abstract:  In IEEE 802.11 Wireless Local Area Networks (WLANs) a rate adaptation algorithm is employed

as a frame transmission rate controller. The Rate controller algorithm Minstrel-HT was developed as

the default rate adaptation in the Linux kernel for WiFi standards IEEE 802.11n and 802.11ac, which

expanded upon the IEEE 802.11g standard Minstrel algorithm. Minstrel-HT performs by dynamically

selecting data rates based on the current condition of the channel to increase throughput, achieve higher

network performance and minimise packet loss [1].

This thesis focuses on analyzing various aspects of network performance and the rate selections

made by the Minstrel-HT algorithm. Through this analysis, we gain insights into better optimization

strategies. As data transmission rates can vary in unsupervised scenarios compared to supervised ex-

periments, understanding the decision-making process of the Minstrel-HT algorithm is essential. By

examining different aspects of the channel environment, we can explore new directions for optimizing

the channel.

The thesis introduces a Python-based quantitative analysis tool that enables the examination of mon-

itored data from the Linux kernel’s mac80211, providing a comprehensive view of the Minstrel-HT

algorithm’s decision-making in various scenarios. By observing the results of data transmissions in de-

tail and presenting different analytic plots, we can identify important details that influence transmission

rates. This tool also facilitates the exploration of alternative optimization algorithms, allowing for a

comparison of their effectiveness in improving transmission rates selection methods.
