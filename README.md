# Aspect-Based Sentiment Analysis for Hotels

## Introduction
Phân tích tình cảm dựa trên khía cạnh (Aspect-Based Sentiment Analysis - ABSA) là một kỹ thuật phân tích dữ liệu văn bản theo khía cạnh và xác định tình cảm cho từng khía cạnh. Phân tích tình cảm dựa trên khía cạnh có thể được sử dụng để phân tích phản hồi của khách hàng với các khía cạnh khác nhau của sản phẩm hoặc dịch vụ.

<img src="./Image/vidu.png" width="400"/>

## Dataset
Bộ dữ liệu được xây dựng với quy trình nghiêm ngặt nhằm tạo ra một bộ dữ liệu chất lượng cao để tiến hành phân tích tình cảm dựa trên khía cạnh, với hơn 8,000 bình luận được thu thập từ nền tảng đặt phòng [traveloka](https://www.traveloka.com/en-vn/)  cùng với hơn 36,000 khía cạnh được xác định. Được chúng tôi chia ngẫu nhiên thành các tập Train, Dev, Test theo tỉ lệ 6:2:2.

## Training and Evaluation



## Results
<table>
<thead>
  <tr>
    <th rowspan="2">Method</th>
    <th colspan="3">Hotel</th>
  </tr>
  <tr>
    <th>Precision</th>
    <th>Recall</th>
    <th>F1-score</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td align="center">LR + Tfidf</td>
    <td align="center">59.53</td>
    <td align="center">72.74</td>
    <td align="center">65.47</td>
  </tr>
  <tr>
    <td align="center">Multi NB + Tfidf</td>
    <td align="center">76.54</td>
    <td align="center">33.38</td>
    <td align="center">46.48</td>
  </tr>
  <tr>
    <td align="center">LinearSVC + Tfidf</td>
    <td align="center">-</td>
    <td align="center">-</td>
    <td align="center">82.06</td>
  </tr>
  <tr>
    <td align="center">LR + CV</td>
    <td align="center">76.54</td>
    <td align="center">33.38</td>
    <td align="center">46.48</td>
  </tr>
  <tr>
    <td align="center">Multi NB + Cv</td>
    <td align="center">76.54</td>
    <td align="center">33.38</td>
    <td align="center">46.48</td>
  </tr>
</tbody>
</table>
