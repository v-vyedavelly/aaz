# [Command] _communication email domain sender-username create_

Create a new SenderUsername resource under the parent Domains resource or update an existing SenderUsername resource.

## Versions

### [2023-04-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb21tdW5pY2F0aW9uL2VtYWlsc2VydmljZXMve30vZG9tYWlucy97fS9zZW5kZXJ1c2VybmFtZXMve30=/2023-04-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.communication/emailservices/{}/domains/{}/senderusernames/{} 2023-04-01 -->

#### examples

- Create a sender username
    ```bash
        communication email domain sender-username create --domain-name DomainName --email-service-name ResourceName -g ResourceGroup --sender-username SenderUsername --username Username --display-name DisplayName
    ```
