# jdk

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/patflynn/jdk/actions/workflows/release.yaml/badge.svg)](https://github.com/patflynn/jdk/actions/workflows/release.yaml)

WORK IN PROGRESS

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/jdk:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `latest` | `sha256:03b8aea5111387a066dfb04e55073ca71a92a9de3568c872baf42433fa2b28f6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:03b8aea5111387a066dfb04e55073ca71a92a9de3568c872baf42433fa2b28f6) |  |



## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/jdk:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/jdk:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/jdk"
      },
      "image": {
        "docker-manifest-digest": "sha256:03b8aea5111387a066dfb04e55073ca71a92a9de3568c872baf42433fa2b28f6"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "2a834528e441998401ec93fbde79800d51a70fc8",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/jdk",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIGmZk4c1m2KCf2S+h2rE1uMmjbN5bjrAyrQVx4RBP5u5AiEAzHESP2KRXK+kaGsp3YOg6NlWGm9wpmjzIleXlKd2lx8=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIxZTZjNmM4Y2ZiNTZhY2Q2MTNmY2Y4MmEyNTk2NzJhNmI5NmU2Y2ZjZmVkNjUyNWFlZTE3ZjU2MWVhYjczOGRjIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURoUHlnVEloQ2wvbnZ2cTNlM2VUTjlxai9sdm5DSzIvWFgwSXEyQ1dDSVpnSWdRZWV2SWRMS1BYeGhVSEJsMEpuMHV0eTd4dEQrZXFnSGd4UXk1REpVZHZJPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUndWRU5EUVhsMVowRjNTVUpCWjBsVldVTlljV1ZEUXpWUlR5dHJjWEl3WmtOSmNURXpWMWRDVGpsVmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1ROTlJFVXhUMVJSTTFkb1kwNU5ha2w0VFVSSk0wMUVTWGRQVkZFelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVV5U0dOQlVtdzVRa3hKYm1GTVF6aHljV2hOWmpsTFVGb3pRV3BPUTJ3MWNFaFJZWFVLT1RaclFXZzBhbGxZVjJGWk4yTkZTVk5ZWmt3clUybGxiV2g2YjBSVGVuSk9ObW95WTJKWGFXbE5kRFprVEhkTFYzRlBRMEZyYjNkblowcEhUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZyY0VKVENtTkpUbGdyWjFCT1pubHNRVVIwTnpscFVHcHRLMkZqZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDFwUldVUldVakJTUVZGSUwwSkdjM2RYV1ZwWVlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5Y0d0aGVUaDFXakpzTUdGSVZtbE1NMlIyWTIxMGJXSkhPVE5qZVRsNVdsZDRiRmxZVG14TWJteG9ZbGQ0UVdOdFZtMWplVGx2Q2xwWFJtdGplVGwwV1Zkc2RVMUVhMGREYVhOSFFWRlJRbWMzT0hkQlVVVkZTekpvTUdSSVFucFBhVGgyWkVjNWNscFhOSFZaVjA0d1lWYzVkV041Tlc0S1lWaFNiMlJYU2pGak1sWjVXVEk1ZFdSSFZuVmtRelZxWWpJd2QwWm5XVXRMZDFsQ1FrRkhSSFo2UVVKQloxRkpZekpPYjFwWFVqRmlSMVYzVG1kWlN3cExkMWxDUWtGSFJIWjZRVUpCZDFGdlRXMUZORTE2VVRGTmFtaHNUa1JSZUU5VWF6Uk9SRUY0V2xkTk5VMHlXbWxhUjFVelQxUm5kMDFIVVRGTlYwVXpDazFIV21wUFJFRmpRbWR2Y2tKblJVVkJXVTh2VFVGRlJVSkJOVVJqYlZab1pFZFZaMVZ0Vm5OYVYwWjZXbFJCYWtKbmIzSkNaMFZGUVZsUEwwMUJSVVlLUWtKV2FtRkhSbkJpYldReFdWaEthMHhYYkhSWlYyUnNZM2s1Y1ZwSGMzZElVVmxMUzNkWlFrSkJSMFIyZWtGQ1FtZFJVR050Vm0xamVUbHZXbGRHYXdwamVUbDBXVmRzZFUxSlIwdENaMjl5UW1kRlJVRmtXalZCWjFGRFFraDNSV1ZuUWpSQlNGbEJRMGREVXpoRGFGTXZNbWhHTUdSR2NrbzBVMk5TVjJOWkNuSkNXVGwzZW1wVFltVmhPRWxuV1RKaU0wbEJRVUZIUlVaNWNUa3pVVUZCUWtGTlFWSjZRa1pCYVVJMmJXMXZjaXRxUVhodVYzWXJUbXBvWlZkak0yVUtZMlJyYm5oV0swczFRemRMYVd0d1JWZFlNRkJGWjBsb1FWQlJlV0ZyZG5CMU9XUjFjVlF2YkdWM1ZrdE9kMHMzVW5kdk1rcERNekUxVkRSWWFHbGxRZ281Tm5GelRVRnZSME5EY1VkVFRUUTVRa0ZOUkVFeVowRk5SMVZEVFVZMFpGWnFLMUYzUW1sU1JuSkdSR3hxYWtkb2R6SnhRV1JKVGk4emFVNW9jaTh5Q21oUWRpOW9aV053VFdVdlJtOUljMFZQVjNsUU5VbERjRkE0V25SNFVVbDRRVXMzTXpoMlNYQlRVMnczZEU1alYwczBWall6UmxkM2VXOU9ZVWN5UTJRS1pTdGhWbko2UTBVcmJYUnhRVnA0VWpScFpqUkNWVlp2Tml0M1MzaElObVZFUVQwOUNpMHRMUzB0UlU1RUlFTkZVbFJKUmtsRFFWUkZMUzB0TFMwSyJ9fX19",
          "integratedTime": 1666835989,
          "logIndex": 5948238,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/jdk/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/jdk",
      "githubWorkflowSha": "2a834528e441998401ec93fbde79800d51a70fc8",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3333921163",
      "sha": "2a834528e441998401ec93fbde79800d51a70fc8"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [melange](https://github.com/chainguard-dev/melange) and [apko](https://github.com/chainguard-dev/apko).

