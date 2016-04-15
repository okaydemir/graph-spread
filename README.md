# graph-spread
C++ spreading disease in a graph

# Intro
This project is about Byteotia; a country consisting of N cities connected via M bidirectional roads.
Everything was going great in Byteotia until one day, this beautiful land was struck with a terrible and
incurable disease. The disease appeared out of nowhere, and infected K different cities within one
night. As if this was not enough, this disease kept spreading. At each day, cities that are directly
connected to one of the already infected cities gets infected. This infection spread for a total of T days
until the queen of Byteotia decided to take action; and ordered a country-wide quarantine, which stopped
the infection from furthermore spreading. However it was too late for the cities that were already
infected; they had to be removed completely from Byteotia. Doing so, however, made it so that the
remaining cities in Byteotia were no longer connected, thus Byteotia had to be separated into individual
connected states.

# Input Format
* In the first line, four space separated integers; the number of cities N (2<=N<=100 000), the
number of bidirectional roads M (2<=M<=1 000 000), the number of cities infested in the first
night K (1<=K<=N), and the amount of days passed T (1<=T<=N) in which the disease spread.
* In each of the following M lines, two integers a i and b i (1<= a i , b i <= N) describing a single
bidirectional road.
* In the following K lines, one integer c i per line; the indexes of the K cities initially infected
with the disease.

# Output Format:
* In a single line; the number of connected states Byteotia needs to be separated into.
