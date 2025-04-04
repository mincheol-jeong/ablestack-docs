
# VPN 고객 게이트웨이

## 개요
 VPN 고객 게이트웨이는 외부 네트워크와 ABLESTACk 클라우드 인프라 간의 안전한 연결을 위한 기능입니다. 이 기능을 사용하면 ABLESTACK 클라우드 가상머신이 사용자의 온프레미스 네트워크와 보안된 VPN 터널을 통해 연결할 수 있습니다. 기본적으로 VPN 고객 게이트웨이는 ABLESTACk 클라우드와 외부 네트워크 간의 IPsec VPN 연결을 설정하고 관리하는 데 사용됩니다. 이 연결은 데이터를 암호화하고 보호하여 인터넷을 통해 안전하게 데이터를 전송할 수 있도록 합니다.

## 목록 조회

1. VPN 고객 게이트웨이 목록을 확인하는 화면입니다.
    생성된 VPN 고객 게이트웨이 목록을 확인하거나 VPN 고객 게이트웨이 추가 버튼을 클릭하여 VPN 고객 게이트웨이 추가할 수 있습니다.
    ![vpn 고객 게이트웨이 목록 조회](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-list.png){ align=center }

## VPN 고객 게이트웨이 추가

1. VPN 고객 게이트웨이 추가 버튼 클릭 하여 VPN 고객 게이트웨이 추가 화면을 호출합니다.
    
    ![sts vpn 고객 게이트웨이 추가 버튼](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-add-btn.png){ align=center }
    
    * **VPN 고객 게이트웨이 추가** 버튼을 클릭하여 VPN 고객 게이트웨이 추가 화면을 호출합니다.

2. VPN 고객 게이트웨이 추가를 위한 항목을 입력합니다.
    ![vpn 고객 게이트웨이 추가1](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-add1.png){ align=center }
    
    * **이름** 을 입력합니다.
    * **게이트웨이** 를 입력합니다.
    * **CIDR 목록** 을 입력합니다.
    * **IPsec 사전 공유키** 를 입력합니다.
    * **IKE 암호화** 를 선택합니다.
    * **IKE 해시** 를 선택합니다.
    * **IKE 버전** 을 선택합니다.
    * **IKE DH** 를 선택합니다.
    * **ESP 암호화** 를 선택합니다.
    * **ESP 해시** 를 선택합니다.
    * **완벽한 순방향 비밀성** 을 선택합니다.
    * **IKE 유효기간(초)** 을 입력합니다.
    
    ![vpn 고객 게이트웨이 추가2](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-add2.png){ align=center }
    
    * **ESP 유효기간(초)** 을 입력합니다.
    * **확인** 버튼을 클릭하여 VPN 고객 게이트웨이를 생성합니다.

## 상세 탭

1. VPN 고객 게이트웨이에 대한 상세정보를 조회하는 화면입니다. 해당 VPN 고객 게이트웨이의 이름, 아이디, 게이트웨이, CIDR 목록, IPsec 사전 공유 키, IKE 정책, IKE 유효시간(초), IKE 버전, ESP 정책, ESP 유효기간(초), Dead 피어 감지, 연결 분할, ESP 패킷의 UDP 캡슐화 강제, 계정, 도메인 등의 정보를 확인할 수 있습니다.

    ![vpn 고객 게이트웨이 상세 탭](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-detail-tab.png){ align=center }

## 편집

1. 해당 VPC 고객 게이트웨이의 정보를 업데이트합니다.

    ![vpn 고객 게이트웨이 편집 버튼](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-update-btn.png){ align=center }

    * **편집** 버튼을 클릭하여 VPC 고객 게이트웨이 편집 화면을 호출합니다.

    ![vpn 고객 게이트웨이 편집 버튼](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-update.png){ align=center }

    * 수정할 **항목** 을 입력합니다.
    * **확인** 버튼을 클릭하여 VPC 고객 게이트웨이를 편집 합니다.

## VPN 고객 게이트웨이 삭제

1. VPN 고객 게이트웨이을 삭제할 수 있습니다.

    ![vpn 고객 게이트웨이 삭제 버튼](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-remove-btn.png){ align=center }

    * **VPN 고객 게이트웨이 삭제** 버튼을 클릭하여 VPN 고객 게이트웨이 삭제 화면을 호출합니다.

    ![vpn 고객 게이트웨이 삭제 화면](../../assets/images/admin-guide/mold/network/vpn-customer-gateway/vpn-customer-gateway-remove.png){ align=center }

    * **확인** 버튼을 클릭하여 VPN 고객 게이트웨이를 삭제합니다.
