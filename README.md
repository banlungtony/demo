# demo
json data
Normal case

input: {
  username: "userInput",
  password: "userInput",
  uuid: "getDeviceId"
}
output: {
    "statuscode": "11",
    "statusdesc": "Success Validate Login",
    "data": [
        {
            "dsaCode": "MAA417",
            "dsaName": "UAT username",
            "dsaMobileNo": "",
            "dsaTeamCode": "TMM153",
            "dsaBranchCode": "",
            "dsaPosition": "STAFF"
        }
    ],
    "session": "xxxxx-xxxx-xxxx-xxxxxxxx-xxxxx",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJkc2FfY29kZSI6Ik1BQTQxNyIsImRzYV9uYW1lIjoiVUFU4LiE4Li44LiTIOC4k-C4seC4kOC4mOC4ouC4siDguJXguLHguJnguJXguLTguInguLLguKLguLLguIHguKMgIiwiZHNhX21vYmlsZSI6IjA4MTkxNDkwMDQiLCJkc2Ffcm9sZSI6ImRzYSIsImlhdCI6MTUyOTAzNjMzMiwiZXhwIjoxNTI5MDUwNzMyfQ.rY0Awnstoc7C36uyGs0R3l8i7AXe6znzs3ZGKnBNZhE"
}

// -------------------------------------------------------------------------------------------------------

Finger Print case
input: {
  username: "read data.dsaCode",
  password: "read session",
  uuid: "getDeviceId"
}

output: {
  "statuscode": "11",
    "statusdesc": "Success Validate Login",
    "data": [
        {
            "dsaCode": "MAA417",
            "dsaName": "UAT username ",
            "dsaMobileNo": "",
            "dsaTeamCode": "TMM153",
            "dsaBranchCode": "",
            "dsaPosition": "STAFF"
        }
    ],
    "session": "xxxxx-xxxx-xxxx-xxxxxxxx-xxxxx",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJkc2FfY29kZSI6Ik1BQTQxNyIsImRzYV9uYW1lIjoiVUFU4LiE4Li44LiTIOC4k-C4seC4kOC4mOC4ouC4siDguJXguLHguJnguJXguLTguInguLLguKLguLLguIHguKMgIiwiZHNhX21vYmlsZSI6IjA4MTkxNDkwMDQiLCJkc2Ffcm9sZSI6ImRzYSIsImlhdCI6MTUyOTAzNjMzMiwiZXhwIjoxNTI5MDUwNzMyfQ.rY0Awnstoc7C36uyGs0R3l8i7AXe6znzs3ZGKnBNZhE"

}
