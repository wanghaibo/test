apiVersion: v1
clusters:
- cluster:
    server: https://10.0.0.194:6443
    certificate-authority-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSURPekNDQWlPZ0F3SUJBZ0lCQURBTkJna3Foa2lHOXcwQkFRc0ZBREErTVNjd0R3WURWUVFLRXdob1lXNW4KZW1odmRUQVVCZ05WQkFvVERXRnNhV0poWW1FZ1kyeHZkV1F4RXpBUkJnTlZCQU1UQ210MVltVnlibVYwWlhNdwpJQmNOTWpFeE1USTBNRGt6TnpBMVdoZ1BNakExTVRFeE1UY3dPVE0zTURWYU1ENHhKekFQQmdOVkJBb1RDR2hoCmJtZDZhRzkxTUJRR0ExVUVDaE1OWVd4cFltRmlZU0JqYkc5MVpERVRNQkVHQTFVRUF4TUthM1ZpWlhKdVpYUmwKY3pDQ0FTSXdEUVlKS29aSWh2Y05BUUVCQlFBRGdnRVBBRENDQVFvQ2dnRUJBTXJmM1dUSDJVU2hOVHAzbEtqeAp2cE5heDY3MlBjSkZVOWIweWd3ang4bEJoQlZrcEkrWERhU09QSlZuN3JId0hVRUd0Tll6aFZPTUp3ZFhRc1dWCkpFMTB4N29UamJGVmRqY2lGRmQ2THIvc010ZEVVUkYrM2xRbk15S0REdVBqQVJCb1BXdW9ISExKRVlTZmtjRnIKRXlDZmFZalVNSjk0bGE2RVFZd2JwQW5raXR2S0lmUElHSHlmRURVbzY3TW9ZS0hHU2xqcFhxRi9Mcm5BMWd0RgplelNqZlVxY04xWWlGWHY2MCtJd0tQOVRRRkRMYUhJZ2xWYzNVNFBhaHEwQUpWaHJoZWxwemEvd01aakVaT0t3ClduYXdtdERBczNUc3VXeUxxZEtNYkowQ1VPYzVLamFtdml2ZW9uUkpMbFczU0lSREVrNjJiU1pScjc2TjBrSk0KUFFrQ0F3RUFBYU5DTUVBd0RnWURWUjBQQVFIL0JBUURBZ0trTUE4R0ExVWRFd0VCL3dRRk1BTUJBZjh3SFFZRApWUjBPQkJZRUZFbVFtNVg1aVRtdWJERlE5MStpaG9qYlJScXdNQTBHQ1NxR1NJYjNEUUVCQ3dVQUE0SUJBUUNYCm9sSlZGVjNRZFFvYUQ5amZjajBMcUZRYm5lbkt0dU1iSjAwcDZ2dURoYThjT0puYXRLY29LTHBFUThIWjJZb24KcG93eHFSNXRGUXBQRmlDR25PREVSTkgyTTB3dlk2U2hPZmt3eTJMRUpxdEowd0tUemVoampmVVZpbldQY3QyZQpETzNJTU9RTXJYU2h2aERiOU4xMGZqT3B3RmVxS0lpUmhXTXN3SDhPN0JOY0kvVWUyUzNjWTV3WmlWRmJ1ZUNYCnNqOVEvb29kRWI1NDVGS0JlNHRHby9pSGQwZGRPT2JDVU84Zk9NV1JRZDVXMHk1S3YxZnlKcDdqeTBNOG1uR0gKRW92SGp5UDFOaXdmalJ2Z0VkbGcvZGZpYWQzR3A3S3ZkeHRNLzVZRDc0amxPVjYyWWdCdzRwNzJXdVZUdDJ6NQpuYi84aWJSdU9URG9sT09WNnVVcwotLS0tLUVORCBDRVJUSUZJQ0FURS0tLS0tCg==
  name: kubernetes
contexts:
- context:
    cluster: kubernetes
    user: "kubernetes-admin"
  name: kubernetes-admin-c01a4f1f1615144df97cb59be880b60a4
current-context: kubernetes-admin-c01a4f1f1615144df97cb59be880b60a4
kind: Config
preferences: {}
users:
- name: "kubernetes-admin"
  user:
    client-certificate-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSUQvRENDQXVTZ0F3SUJBZ0lEU2xrWE1BMEdDU3FHU0liM0RRRUJDd1VBTUdveEtqQW9CZ05WQkFvVElXTXcKTVdFMFpqRm1NVFl4TlRFME5HUm1PVGRqWWpVNVltVTRPREJpTmpCaE5ERVFNQTRHQTFVRUN4TUhaR1ZtWVhWcwpkREVxTUNnR0ExVUVBeE1oWXpBeFlUUm1NV1l4TmpFMU1UUTBaR1k1TjJOaU5UbGlaVGc0TUdJMk1HRTBNQjRYCkRUSXhNVEV5TkRBNU16RXdNRm9YRFRJME1URXlNekE1TXpZek1Gb3dTREVWTUJNR0ExVUVDaE1NYzNsemRHVnQKT25WelpYSnpNUWt3QndZRFZRUUxFd0F4SkRBaUJnTlZCQU1UR3pFMk5UTXdOalU1TnpBMk1UVTJOREF0TVRZegpOemMwTmpVNU1EQ0NBU0l3RFFZSktvWklodmNOQVFFQkJRQURnZ0VQQURDQ0FRb0NnZ0VCQU4vUlJNTkJqdjNVCm9GTW5iQVRCNEE4SXhXbHFHSnFoK3lqVFVSWDcxVVRmTklHckFYUEM4TmR2ME5rYlg1UmxjditpMXVKQ092YkYKM0docHhjTXcwNkw0YmRpMUJVQXFGelNFeEU1ZjR4a2Rja2ZmQlJ0Z0IvMEdCTlg2ZjJ0ZjNteFg2SWErOExZZgpNdVBGeHFMWFUzRGJZU1hUYVZWL3V3a21lejVlV2s3NXJVTEU2TkdFOE1RYnlUcHA0LzUyL1kyZElDWWtsZUE2CmpSaXl4V3RMbllabnh4TmsxTFVRaVlnYTJQeDNFYVRXZnpjODNyZGQ2SmtMRlhGVDlIRU5vRXBaL0NIUnJzcUwKWkEwZjZZc0NOenNzWEREV0NTMVVad2R6RWVQQlBsR3N2dnNQTjI1NStXUC82TFgvQWdEUDhiclNnS09RWUZjKwpKY3V3VTBqaG5Nc0NBd0VBQWFPQnpEQ0J5VEFPQmdOVkhROEJBZjhFQkFNQ0I0QXdFd1lEVlIwbEJBd3dDZ1lJCkt3WUJCUVVIQXdJd0RBWURWUjBUQVFIL0JBSXdBREFmQmdOVkhTTUVHREFXZ0JTOEMzRFVLREh1VytLeW9hMzQKVHk4SFlDVDN6VEE4QmdnckJnRUZCUWNCQVFRd01DNHdMQVlJS3dZQkJRVUhNQUdHSUdoMGRIQTZMeTlqWlhKMApjeTVoWTNNdVlXeHBlWFZ1TG1OdmJTOXZZM053TURVR0ExVWRId1F1TUN3d0txQW9vQ2FHSkdoMGRIQTZMeTlqClpYSjBjeTVoWTNNdVlXeHBlWFZ1TG1OdmJTOXliMjkwTG1OeWJEQU5CZ2txaGtpRzl3MEJBUXNGQUFPQ0FRRUEKaHNvWlJuODN4NnF3QmNHRCs1SkxhQlNjNVhVMjNJMmpkZ1l0N0hlcFVyUG1ORDJCampTbHgvR3FSZnowMlZ0SApIeG8xQUZ2dm1kRWl1eHNlWUZrb1cwcVR5Umx1enNXT0hub0lPZTRsWGdtNjFlK3A5KzM3STN2QkgwMGlXbFVxCmFzVVhNc1c0SjNEc3MyTE1IcUErcEFvT0M3UFN1UEh1eVUvNmI2TFdWY01jSGFQUXF2Sm5oMlY4OHREdlFmQ1QKeXZvTmhadjdldk9wS0ZRT0hxN3pzK1dVbGF6QkptdGUyM3RBQlBKZ0srRGtzNnF3OFlaaTc5ZnREVlY4dndDYQptSHljSnF5SXdvTWxkK29uSktxVTM3YVNkVEQ5QjIreU05SU1rV3lvVEMrUjc2bzNiNzFPNkZhbkhvamd5cGFhClJ5dVFoTDlGYVVaamlwclllUFlBNHc9PQotLS0tLUVORCBDRVJUSUZJQ0FURS0tLS0tCi0tLS0tQkVHSU4gQ0VSVElGSUNBVEUtLS0tLQpNSUlEb2pDQ0F3dWdBd0lCQWdJRFNsa1dNQTBHQ1NxR1NJYjNEUUVCQ3dVQU1HSXhDekFKQmdOVkJBWVRBa05PCk1SRXdEd1lEVlFRSURBaGFhR1ZLYVdGdVp6RVJNQThHQTFVRUJ3d0lTR0Z1WjFwb2IzVXhFREFPQmdOVkJBb00KQjBGc2FXSmhZbUV4RERBS0JnTlZCQXNNQTBGRFV6RU5NQXNHQTFVRUF3d0VjbTl2ZERBZUZ3MHlNVEV4TWpRdwpPVE14TURCYUZ3MDBNVEV4TVRrd09UTTJNamRhTUdveEtqQW9CZ05WQkFvVElXTXdNV0UwWmpGbU1UWXhOVEUwCk5HUm1PVGRqWWpVNVltVTRPREJpTmpCaE5ERVFNQTRHQTFVRUN4TUhaR1ZtWVhWc2RERXFNQ2dHQTFVRUF4TWgKWXpBeFlUUm1NV1l4TmpFMU1UUTBaR1k1TjJOaU5UbGlaVGc0TUdJMk1HRTBNSUlCSWpBTkJna3Foa2lHOXcwQgpBUUVGQUFPQ0FROEFNSUlCQ2dLQ0FRRUF2eVFCY2pFcmVVWFJVSzdnSkhQRW5LNzBKNS9nUGdZSW14bXFKelZNCjNRV1cvNjJqMTNBQ0FNSFJsdktWekNXMFAvWExpSjRUNGwrRDNkc3dVbTM2RFVCZjAzVXBkQ2h4cUs5ZUQzZlkKTHk4MS9tQ3pYMFpmYVgzNjhmV0pJQmYrMlZRWjdsLzJJbmkzZU9MRktUcjlLanpUblNWN2dzblFnYi9ma05YdgpscWlTVGkrdzJZRjBJOGdlZTdqdjJ0VVFua2hEZE52ZzdJOFFWTHJJeloyZTc3SzdrVHIxYkljMm1tZWx2K2tVCmZZL0hlTzJZeGlZS2FnRnhNNnZDc01zd2R6U0tTcEVtYmdvcTladmx2M1kvT0kwcVFtVVBnZ1NCSVh6TS9mNUMKZjEvclpYb0w0T0R1cHllUU8wR1JxdE5ZNjVvWmwzVmo1cEJHOXk2R1lUMGQyd0lEQVFBQm80SFpNSUhXTUE0RwpBMVVkRHdFQi93UUVBd0lDckRBUEJnTlZIUk1CQWY4RUJUQURBUUgvTUIwR0ExVWREZ1FXQkJTOEMzRFVLREh1ClcrS3lvYTM0VHk4SFlDVDN6VEFmQmdOVkhTTUVHREFXZ0JTRld2L2RJODBsYjFoQmI1NXRSVG1iV0gxMS96QTgKQmdnckJnRUZCUWNCQVFRd01DNHdMQVlJS3dZQkJRVUhNQUdHSUdoMGRIQTZMeTlqWlhKMGN5NWhZM011WVd4cAplWFZ1TG1OdmJTOXZZM053TURVR0ExVWRId1F1TUN3d0txQW9vQ2FHSkdoMGRIQTZMeTlqWlhKMGN5NWhZM011CllXeHBlWFZ1TG1OdmJTOXliMjkwTG1OeWJEQU5CZ2txaGtpRzl3MEJBUXNGQUFPQmdRQklKdFprTm0vUFpDZjMKaEVWWkE3L2ljS3dNSXZCMTMxWFE2RXBkeENydDBDSUZoTHFtaWZoY2xOWUhXcGd6RytQYW9sM2VmeHlvSm9tUgphazkrQVp6eFdQczNIWWd2cnFUUjJUNldkNTI4amswNldOVTBLRXRpb3RYWjhkTlpwZUlLYkZ0T3ppSnBCd3MzCmxpRm9mRW9Jd0s2Q0xMcStpa1pIQXBiM1BQN05EQT09Ci0tLS0tRU5EIENFUlRJRklDQVRFLS0tLS0K
    client-key-data: LS0tLS1CRUdJTiBSU0EgUFJJVkFURSBLRVktLS0tLQpNSUlFcEFJQkFBS0NBUUVBMzlGRXcwR08vZFNnVXlkc0JNSGdEd2pGYVdvWW1xSDdLTk5SRmZ2VlJOODBnYXNCCmM4THcxMi9RMlJ0ZmxHVnkvNkxXNGtJNjlzWGNhR25Gd3pEVG92aHQyTFVGUUNvWE5JVEVUbC9qR1IxeVI5OEYKRzJBSC9RWUUxZnAvYTEvZWJGZm9ocjd3dGg4eTQ4WEdvdGRUY050aEpkTnBWWCs3Q1NaN1BsNWFUdm10UXNUbwowWVR3eEJ2Sk9tbmovbmI5alowZ0ppU1Y0RHFOR0xMRmEwdWRobWZIRTJUVXRSQ0ppQnJZL0hjUnBOWi9OenplCnQxM29tUXNWY1ZQMGNRMmdTbG44SWRHdXlvdGtEUi9waXdJM095eGNNTllKTFZSbkIzTVI0OEUrVWF5Kyt3ODMKYm5uNVkvL290ZjhDQU0veHV0S0FvNUJnVno0bHk3QlRTT0djeXdJREFRQUJBb0lCQVFETWZPRkxXQWx4NWlNNAo5Z3FkNmhoeEEvMkJpMXJCWlA4WTFNRC95ZCtYbGlyZDBjUjQ1SUd4QThzWG9RZlppRHJpVHYvdkpyM0NteEgrCkg2MTg0WTVyRm5rZUJuMnVtd1lxaUtibVNIc3ZoaFRVajNHV0NrNGlJYTZuWmIrbTlhYzg2N0JaOC9mdkhXQWMKZEtWQVFHVk85bEN6QTQzNGZNUUEzelM0emZIS3RtTytBTG1iMmpveE5HdnU4QUQ2dElRRERaV2szUk5GOE1mVgoyOFVOeVg1TkRJT1dHVkZiaUV4OUFibnJRUmEvNVlrNGxBOUtBMWJ2aitaMEtFUWVsVnlaWmNCYWIydXVyZ2c5ClkrOVhUSGxMb0dNMG9kNlRzb0hEeWdYU3ZLeERCTXArU0VHOEY1MXI5VWRQQ05vQXhRZzVqdXJCdzNpZkFndzcKR2xRVmZMbVJBb0dCQU9pQTZnYVpaZm1waVQ0VnUvY1kxbFhFOVgwSnRBeEhFR01OOFlLdlV4bk9xTUpFekZqZwpyK2JlTUxGZ2p4T0hmVEhBdGZocHk3eHJKVmx5VWhNaTFCSFRFMlh2VER4SjNHTkdxeVRJK1NIOElpTVFaK3dWClBvaFdUcUM2Sm8rNlJtejhmcms0SmdBN1l5QS9ielNIVEZDSm50a0dBK1hRZ0YrdHpNbnlwSGFUQW9HQkFQWnYKb3UvaGkwOExGWTRUSHRjQ0RZTnNVTmZKYVhQWVIwU2VvRzRWc21mVzhkMGZ4ZzdQbnRKTGhWR3BpREJTTTFQawppNkQ2QVVkSEF4RnFLdjdveDVUT3NzQjlOc3FxZVE5czRYMWJkTEtFZnVSUGdzZTZlR0RNOVk4dmhQRUIzS3FUCnBVQUtxNHR6OFVwRGpoNHlTUXczYjB1dzFIaVE3bHJHOGc0Vy9TdnBBb0dCQU11TFFGWHlxVUcrV0RZUUZQUW4KdkV4dUYzUVZzSmduQm9PUlMyTmJWZWI3OHVYUUVRMmw5cGlvMy93SlNuaVFYdHZWbC9rWHRaTUlRalJpVHRRTgo0NWFQTVNaR0xubUJOLzE1ZW83RG1zZFQwaGJjWC81Z1F0UmNxbzB2S2w4ZGRsWW5YbEdNaEVnanRZNGZ1cDFECjdWMThmYUlGRUJoN1JrZDlBaEd4NktVZEFvR0FjdlZvNE5ZcUVsbHRXTFY2c1huM3E5TWZjMG8xc3lDMVBrRngKUFdsSnJEOE0zTVl4c2o4UUs3R25JNDBlUnN4UnZWVGovZGdpT0luYjJJZmFQc2VBTXQ2cGJEbjlFVldzMjVGRApMeU0yc1FBMTRYTmw0cDRPQWJvYTR3eWJ5NEcrMnFPOWRyNkRmNjQ2WlJaV2VhZWpnOXRvUTdyZG90Q1pJQ2VtClN3UldYZUVDZ1lCK3dVRGpDc3NuTExOTnpNVDBVbU4vdFR3a2c0dEk2VFZGa3IvNVhoa21VTW11dnhYYWpoc24KYUJDZ3cvMWYzSm1RN0ZERlJ6RVliZTJremNya2NxM2c5SWQzR2F2am9lWlg5QWdsNythY1JDbTJGd3hHaUtQbApobkppeGtJVkhhampOS0YvMUV5dE90ZFFqd1BrcnEwck1wcW5xMi8wNmN4OUROTTBwSC83a3c9PQotLS0tLUVORCBSU0EgUFJJVkFURSBLRVktLS0tLQo=
