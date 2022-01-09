# 데이터베이스 관리

## 데이터베이스 관리

데이터베이스의 정보를 DML, DCL, DDL등을 등록하고 관리합니다.



#### SCHEMA, DOMAIN, TABLE, VIEW, INDEX를 정의하거나 변경 또는 삭제할 때 사용하는 언어입니다.

데이터 베이스 관리자나 데이터베이스 설계자가 사용 합니다.

{% tabs %}
{% tab title="DDL" %}
DDL(Data Definition Language, 데이터 정의어) : 데이터베이스를 정의하는 언어이며, 데이터를 생성, 수정, 삭제하는 등의 데이터의 전체의 골격을 결정하느 역할을 하는 언어입니다.
{% endtab %}

{% tab title="CREATE" %}
CREATE : 데이터베이스, 테이블 등을 생성하는 역할을 합니다.
{% endtab %}

{% tab title="ALTER" %}
ALTER : 테이블을 수정하는 역할을 합니다.
{% endtab %}

{% tab title="DROP" %}
DROP : 데이터베이스, 테이블을 삭제하는 역할을 합니다.
{% endtab %}

{% tab title="TRUNCATE" %}
TRUNCATE : 테이블을 초기화 시키는 역할을 합니다.
{% endtab %}
{% endtabs %}





#### 데이터베이스 사용자가 응용 프로그램이나 질의어를 통하여 저장된 데이터를 실질적으로 처리하는데 사용하는 언어 입니다.

데이터베이스 사용자와 데이터베이스 관리 시스템 간의 인터페이스를 제공합니다.

{% tabs %}
{% tab title="DML" %}
DML(Data Manipulation Language, 데이터 조작어) 정의된 데이터베이스에 입력된 레코드를 조회하거나 수정하거나 삭제하는 등의 역할을 하는 언어를 말합니다.
{% endtab %}

{% tab title="SELECT" %}
SELECT : 데이터를 조회하는 역할을 합니다.
{% endtab %}

{% tab title="INSERT" %}
INSERT : 데이터를 삽입하는 역할을 합니다.
{% endtab %}

{% tab title="UPDATE" %}
UPDATE : 데이터를 수정하는 역할을 합니다.
{% endtab %}

{% tab title="DELETE" %}
DELETE : 데이터를 삭제하는 역할을 합니다.
{% endtab %}
{% endtabs %}





#### 데이터를 제어하는 언어 입니다.

데이터의 보안, 무결성, 회복, 병행 수행제어 등을 정의하는데 사용합니다.

{% tabs %}
{% tab title="First Tab" %}
DCL(Data Control Language, 데이터 제어어) - 데이터베이스에 접근하거나 객체에 권한을 주는등의 역할을 하는 언어를 입니다.
{% endtab %}

{% tab title="GRANT" %}
GRANT : 특정 데이터베이스 사용자에게 특정 작업에 대한 수행권한 부여 합니다.
{% endtab %}

{% tab title="REVOKE" %}
REVOKE : 특정 데이터베이스 사용자에게 특정 작업에 대한 수행 권한을 박탈, 회수 합니다.
{% endtab %}

{% tab title="COMMIT" %}
COMMIT : 트랜잭션의 작업을 취소 및 원래래 복구하는 역할을 합니다.
{% endtab %}

{% tab title="ROLLBACK" %}
ROLLBACK : 트랜잭션의 작업을 취소 및 원래대로 복구하는 역할을 합니다.
{% endtab %}
{% endtabs %}

