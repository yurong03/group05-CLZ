# CLZ CP1 測試資料

本資料夾保存 C baseline 的測試向量與預期輸出。

| 檔案 | 說明 |
|---|---|
| [`test_vectors.txt`](./test_vectors.txt) | 10 組輸入與預期 CLZ 結果 |
| [`expected_output.txt`](./expected_output.txt) | 執行 `clz.c` 後的預期終端輸出 |

測試包含最高位元、不同前導零長度、最低位元，以及全零輸入等案例。
其中 `0x00000000` 是規格定義的邊界值，結果必須為 `32`。
