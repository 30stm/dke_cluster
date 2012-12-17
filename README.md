dke_cluster
===========



이 문서은 dke랩실내에서 분산처리환경에 대한 연구를 하기 위해 작성되어있다.
주로 클러스터 설치에 관하여 다룬다. 

클러스터 설치를 위한 대략적인 순서는 아래와 같다.  

1. 각 컴퓨터에 Ubuntu를 설치한후(계정 설정, SSH 등)
2. 각 PC에 공유기를 이용하여 IP를 부여한다. 
3. Domain name server(bind9)을 이용하여 각 서버에 domain 주소를 부여한다. 
4. cloudera manager를 PC 중 1대에 설치한다.
5. cloudera manager를 이용해 다른 PC들에 cloudera agents, CDH, java 등을 설치한다.

[1 : PC 설정](https://github.com/30stm/dke_cluster/wiki/%EA%B0%81-%EC%BB%B4%ED%93%A8%ED%84%B0-%EC%84%A4%EC%A0%95)  
[2~3 : 네트워크 구성](https://github.com/30stm/dke_cluster/wiki/network-configuration)  
[클러스터 설치] (https://github.com/30stm/dke_cluster/wiki/Cluster-Installation-Manual)



# 모니터 스위치 컴퓨터 별 맵핑

<table>
<tr>
<td>컴퓨터</td>
<td>15</td>
<td>16</td>
<td>17</td>
<td>18</td>
<td>19</td>
<td>20</td>
<td>21</td>
<td>22</td>
<td>23</td>
<td>24</td>
<td>25</td>
</tr>
<tr>
<td>스위치</td>
<td>1</td>
<td>2</td>
<td>3</td>
<td>4</td>
<td>5</td>
<td>6</td>
<td>7</td>
<td>8</td>
<td>9</td>
<td>10</td>
<td>11</td>
</td>
</table>

* 23번 컴퓨터 : 관리자
* 
