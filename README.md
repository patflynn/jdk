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
| `openjdk-17-20221109` | `sha256:ad0036b87381b5a8a91f92be081b5b1a0027f88f52f87664a82b1820c29fe564`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ad0036b87381b5a8a91f92be081b5b1a0027f88f52f87664a82b1820c29fe564) | `amd64` |
| `latest` `openjdk-17` `openjdk-17-20221110` `openjdk-17.0` `openjdk-17.0.5` `openjdk-17.0.5.8` `openjdk-17.0.5.8-r0` | `sha256:78b2d14deafae3a60a72898f410cda21e249d4af7c5317e0b737de29cbbeccfc`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:78b2d14deafae3a60a72898f410cda21e249d4af7c5317e0b737de29cbbeccfc) | `amd64` |
| `openjdk-jre-17-20221109` | `sha256:35f2836f1afa57fa1064e481d2e10e14c756b98a7a54a37cfdf138ebc564342b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:35f2836f1afa57fa1064e481d2e10e14c756b98a7a54a37cfdf138ebc564342b) | `amd64` |
| `openjdk-jre-11-20221109` | `sha256:3805ce10c4eae441ff9a27542dd182477256bc18f537698e5551a18684b5b411`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:3805ce10c4eae441ff9a27542dd182477256bc18f537698e5551a18684b5b411) | `amd64` |
| `openjdk-jre-17` `openjdk-jre-17-20221110` `openjdk-jre-17.0` `openjdk-jre-17.0.5` `openjdk-jre-17.0.5.8` `openjdk-jre-17.0.5.8-r0` | `sha256:a9d6a64a94aaa91df669f7c882719d26052f9f6c0cdaa6ddffeb018878c838c6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a9d6a64a94aaa91df669f7c882719d26052f9f6c0cdaa6ddffeb018878c838c6) | `amd64` |
| `openjdk-jre-11` `openjdk-jre-11-20221110` `openjdk-jre-11.0` `openjdk-jre-11.0.17` `openjdk-jre-11.0.17.8` `openjdk-jre-11.0.17.8-r0` | `sha256:1716238d84fbfc88eed5b06471194edf4092e94d2c4df4e31cc49b6d3a0f3100`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:1716238d84fbfc88eed5b06471194edf4092e94d2c4df4e31cc49b6d3a0f3100) | `amd64` |
| `openjdk-11-20221109` | `sha256:01ab33f239cb9bab311ba4fe63b1f85864de6dd6d0b3119ea7d5ec638a1e4e5a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:01ab33f239cb9bab311ba4fe63b1f85864de6dd6d0b3119ea7d5ec638a1e4e5a) | `amd64` |
| `openjdk-11` `openjdk-11-20221110` `openjdk-11.0` `openjdk-11.0.17` `openjdk-11.0.17.8` `openjdk-11.0.17.8-r0` | `sha256:31c4733dc8a6957f9dba56f987900c28b3cd949b5a11787682c9898dcc7d6d85`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:31c4733dc8a6957f9dba56f987900c28b3cd949b5a11787682c9898dcc7d6d85) | `amd64` |



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
        "docker-manifest-digest": "sha256:78b2d14deafae3a60a72898f410cda21e249d4af7c5317e0b737de29cbbeccfc"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "00c06154dd9eda50122bc936f644df507f34a59b",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQCB+su5cPSrW8K00SeBr4vQeJAJWScshiV3OK0hCHJUMwIhAOQgkrK5K+PYuBEK6e6Nnr7siHJ0fAbbP78WChX89GIk",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIzOTU1ZjlkZGJiYzM5YjI0YzlmZWFmNzgwZmM5M2QzZmZjNTNjODIyNjg2ODBkNGI1YWE3MTM2MDI3ODczMDk3In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJRkhvOFB4WDhOSU93WTFia0crYkxtUnBQMWRaRFFPYjVRZ09uK3B0emI0R0FpQWpWMEV1aHNLMm41QWYwdGFHK25FMEg1NmFpOVJ1N2pGSkhXdDJpUFdkblE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjFla05EUVRCTFowRjNTVUpCWjBsVlVFZGFSV2hOYUdGa0swOUVUVVZ0VjJkQlFVbEROR0pQU1dZNGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlhkTlJFVjNUbFJWZUZkb1kwNU5ha2w0VFZSRmQwMUVSWGhPVkZWNFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVUxTVdFME1FNVJVR3A0YUZWM2NGSnpOa3h2VFhkVGFVZHRjMmRtTnpCcldIWnBSMWdLZVRsb1MzVkhXU3R2Wm5sTU9FczVXbWszVUhabFJFbHJhek5pZWpsS05rWlFVR1UzTjIxNWJtZ3dhazVyU0ZkaVUwdFBRMEZ0UlhkblowcGtUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlVyVlhKVkNrOVBOVWxqTjIxQlUybHZVekpzTWtkamVHTTJja3BWZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRHWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSU1dNeVRtOWFWMUl4WWtkVmR3cE9aMWxMUzNkWlFrSkJSMFIyZWtGQ1FYZFJiMDFFUW1wTlJGbDRUbFJTYTFwRWJHeGFSMFV4VFVSRmVVMXRTbXBQVkUweVdtcFpNRTVIVW0xT1ZFRXpDbHBxVFRCWlZGVTFXV3BCYzBKbmIzSkNaMFZGUVZsUEwwMUJSVVZDUWpSMVdqSnNNR0ZJVm1sTU0yUjJZMjEwYldKSE9UTmplVGw1V2xkNGJGbFlUbXdLVEc1c2FHSlhkM2RLWjFsTFMzZFpRa0pCUjBSMmVrRkNRbEZSV1ZreWFHaGhWelZ1WkZkR2VWcERNWEJpVjBadVdsaE5kbUZYTVdoYU1sWjZUVUl3UndwRGFYTkhRVkZSUW1jM09IZEJVVmxGUkROS2JGcHVUWFpoUjFab1draE5kbUpYUm5CaWFrTkNhWGRaUzB0M1dVSkNRVWhYWlZGSlJVRm5VamxDU0hOQkNtVlJRak5CVGpBNVRVZHlSM2g0UlhsWmVHdGxTRXBzYms1M1MybFRiRFkwTTJwNWRDODBaVXRqYjBGMlMyVTJUMEZCUVVKb1JqaFRXV2xOUVVGQlVVUUtRVVZuZDFKblNXaEJTa3hGVWxSdFdscEZWRGR2ZDNwNE4wMTVjbVpzVFRSYVZubHJXVlp5ZUVKSFIycGlORTVzVm1oa1UwRnBSVUYzZFc5R05VOHJUQXBKYUhkUGFsUmhNekJSTTFGQ01EVmlOV0UwZFVrNFlqWnpjMlZMVGtSWmRFbGhVWGREWjFsSlMyOWFTWHBxTUVWQmQwMUVXbmRCZDFwQlNYZFJUR2hQQ25FNU5XRm5LMDFzZWtaM1NXUjFlWEV5YUhNM1JIVk1Uamx6WkZWRE0xVjFjR2c0VWtRNWF6Rk1RV2hJZUcwMWIyUTRMMDVPVTFORU5UQXJZVUZxUWtrS1QyaEVaVnBxUldFNVEwNUJjMEpxY0hCTk5HczNSbFphYkZvMU9HZG1kME5HY0hKalpFTnFVR0p0WkRKaGVsVkRhR2gxT0ZGQlIzTjFhekJGV25CalBRb3RMUzB0TFVWT1JDQkRSVkpVU1VaSlEwRlVSUzB0TFMwdENnPT0ifX19fQ==",
          "integratedTime": 1668042354,
          "logIndex": 6805196,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "00c06154dd9eda50122bc936f644df507f34a59b",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3433128324",
      "sha": "00c06154dd9eda50122bc936f644df507f34a59b"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [melange](https://github.com/chainguard-dev/melange) and [apko](https://github.com/chainguard-dev/apko).

