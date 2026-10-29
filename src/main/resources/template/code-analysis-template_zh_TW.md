# 程式碼分析報告
## XX-PROJECTNAME-XX 
#### 分支 XX-BRANCH-XX
#### 版本 XX-VERSION-XX 

**撰寫者：XX-AUTHOR-XX**

*日期：XX-DATE-XX*

*分析日期：XX-ANALYSISDATE-XX*

## 簡介
本文件包含 XX-PROJECTNAME-XX 的程式碼分析結果。

XX-DESCRIPTION-XX

## 設定

- 品質設定檔 (Quality Profiles)
    - 名稱：XX-QUALITYPROFILENAME-XX
    - 檔案：XX-QUALITYPROFILEFILE-XX


 - 品質門檻 (Quality Gate)
    - 名稱：XX-QUALITYGATENAME-XX
    - 檔案：XX-QUALITYGATEFILE-XX

## 綜合摘要

### 分析狀態

可靠性 | 安全性 | 安全審查 | 可維護性 |
:---:|:---:|:---:|:---:
XX-RELIABILITY-XX | XX-SECURITY-XX | XX-SECURITYREVIEW-XX | XX-MAINTAINABILITY-XX |

### 品質門檻狀態

| 品質門檻狀態 | XX-QUALITYGATE-XX |
|-|-|

$QUALITY_GATE_STATUS

### 指標

覆蓋率 | 重複率 | 註解密度 | 每個檔案程式碼行數中位數 | 編碼規範遵循率 |
:---:|:---:|:---:|:---:|:---:
XX-COVERAGE-XX % | XX-DUPLICATION-XX % | XX-COMMENTDENSITY-XX % | XX-MEDIANNCLOC-XX | XX-COMPLIANCE-XX %

### 測試

總計 | 成功率 | 略過 | 錯誤 | 失敗 |
:---:|:---:|:---:|:---:|:---:
XX-TOTAL-TESTS-XX | XX-TEST-SUCCESS-RATE-XX % | XX-SKIPPED-TESTS-XX | XX-TEST-ERRORS-XX | XX-TEST-FAILURES-XX

### 技術債明細

$DETAILED_TECHNICAL_DEBT

### 指標範圍

\ | 循環複雜度 | 認知複雜度 | 每個檔案程式碼行數 | 覆蓋率 | 註解密度 (%) | 重複率 (%)
:---|:---:|:---:|:---:|:---:|:---:|:---:
最小值 | XX-MINCOMPLEXITY-XX | XX-MINCOGNITIVECOMPLEXITY-XX | XX-MINNCLOC-XX | XX-MINCOVERAGE-XX | XX-MINCOMMENTDENSITY-XX | XX-MINDUPLICATION-XX
最大值 | XX-MAXCOMPLEXITY-XX | XX-MAXCOGNITIVECOMPLEXITY-XX | XX-MAXNCLOC-XX | XX-MAXCOVERAGE-XX | XX-MAXCOMMENTDENSITY-XX | XX-MAXDUPLICATION-XX

### 程式碼規模

$VOLUME

## 問題

### 依嚴重程度與類型統計問題數量

$ISSUES_COUNT

### 問題清單

$ISSUES_DETAILS

## 安全熱點 (Security Hotspots)

### 依類別與優先順序統計安全熱點數量

$SECURITY_HOTSPOTS_COUNT

### 安全熱點清單

$SECURITY_HOTSPOTS_DETAILS
