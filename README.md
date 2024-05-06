### How to run

```python pacman.py```

- Tự tương tác điều khiển với một file layout tùy chọn (sử dụng thêm -l flag): ví dụ python pacman.py -l trickyClassic

- Yêu câu chạy một thuật toán nào đó (sử dụng -p flag): ví dụ python pacman.py -l mediumClassic -p ExpectimaxAgent

- Yêu cầu chạy một thuật toán nào đó với số tầng mong muốn trong game tree (số bước nhìn trước), ví dụ: python pacman.py -l mediumClassic -p MinimaxAgent -a depth=3

- Yêu cầu chạy một thuật toán nào đó với số tầng mong muốn trong game tree (số bước nhìn trước) và sử dụng một hàm lượng giá nào đó, ví dụ: python pacman.py -l mediumClassic -p MinimaxAgent -a depth=3,evalFn=betterEvaluationFunction

- Có thể thiết lập random seed cho bằng cách dùng -s flag. Ví dụ python pacman.py -l mediumClassic -p MinimaxAgent -a depth=3,evalFn=betterEvaluationFunction -s 21520449

- Có thể sử dụng thêm option --frameTime 0 để rút ngắn thời gian simulation.
