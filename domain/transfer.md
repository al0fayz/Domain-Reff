```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
    <epp xmlns="urn:ietf:params:xml:ns:epp-1.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:domain="urn:ietf:params:xml:ns:domain-1.0" xsi:schemaLocation="urn:ietf:params:xml:ns:epp-1.0 epp-1.0.xsd">
      <response>
        <result code="1301">
          <msg>Command completed successfully; ack to dequeue</msg>
        </result>
        <msgQ count="116" id="342334">
          <qDate>2022-10-11T23:00:05.0Z</qDate>
          <msg>Transfer Successful</msg>
        </msgQ>
        <resData>
          <domain:trnData xmlns:domain="urn:ietf:params:xml:ns:domain-1.0">
            <domain:name>ajv.id</domain:name>
            <domain:trStatus>serverApproved</domain:trStatus>
            <domain:reID>digitalreg</domain:reID>
            <domain:reDate>2022-10-06T22:58:41.0Z</domain:reDate>
            <domain:acID>pandi</domain:acID>
            <domain:acDate>2022-10-11T22:58:41.0Z</domain:acDate>
            <domain:exDate>2023-12-23T00:00:00.0Z</domain:exDate>
          </domain:trnData>
        </resData>
        <trID>
          <svTRID>90b4b82d-7ba3-41b8-b9e7-7889a0ed7b8e</svTRID>
        </trID>
      </response>
    </epp>
```

```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
    <epp xmlns="urn:ietf:params:xml:ns:epp-1.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:domain="urn:ietf:params:xml:ns:domain-1.0" xsi:schemaLoc ▶
      <response>
        <result code="1301">
          <msg>Command completed successfully; ack to dequeue</msg>
        </result>
        <msgQ count="77" id="347779">
          <qDate>2022-11-09T02:57:53.0Z</qDate>
          <msg>Transfer Requested</msg>
        </msgQ>
        <resData>
          <domain:trnData xmlns:domain="urn:ietf:params:xml:ns:domain-1.0">
            <domain:name>email.id</domain:name>
            <domain:trStatus>clientRejected</domain:trStatus>
            <domain:reID>pandi</domain:reID>
            <domain:reDate>2022-11-09T02:57:53.0Z</domain:reDate>
            <domain:acID>pandi</domain:acID>
            <domain:acDate>2022-11-14T02:57:53.0Z</domain:acDate>
            <domain:exDate>2025-11-03T00:00:00.0Z</domain:exDate>
          </domain:trnData>
        </resData>
        <trID>
          <svTRID>caea2205-165e-45f7-9c5f-4a4f22d0cf6f</svTRID>
        </trID>
      </response>
    </epp>
```
