import scapy.all as sc

def packet_sniffer(packet):
    print(packet.summary())  # Prints the summary of each packet

sc.sniff(prn=packet_sniffer, count=10)  # Captures 10 packets
