# Lab05 – Tìm kiếm đối kháng và trò chơi

Nhóm: Châu Hải Đăng MSSV: 3123410075


## Các file

| File | Nội dung |
|---|---|
| `tictactoe.py` | Mô hình trò chơi Tic-Tac-Toe dùng chung |
| `tictactoe_definitions.ipynb` | Bài 1: định nghĩa trò chơi |
| `tictactoe_and_or_tree_search.ipynb` | Bài 2: AND-OR Tree Search |
| `tictactoe_alpha_beta_tree_search.ipynb` | Bài 3: Minimax và Alpha-Beta |
| `tictactoe_heuristic_alpha_beta_tree_search.ipynb` | Bài 4: Alpha-Beta với heuristic và cutoff |
| `tictactoe_pure_monte_carlo_search.ipynb` | Bài 5: Pure Monte Carlo Search |
| `tictactoe_monte_carlo_tree_search_restricted.ipynb` | Bài 6: Monte Carlo với UCB1 |
| `tictactoe_interactive.ipynb` | Bài 7: chơi tương tác với `interactive_player` |
| `assignment_connect4.ipynb` | Bài mở rộng: Connect 4 |
| `profiling_code.ipynb`, `store_agent_state_information.ipynb` | Notebook tham khảo (đo thời gian, lưu thông tin tác tử) |
| `baocao_lab05.docx` | Báo cáo |

Bài mở rộng Connect 4.

## Cách chạy

1. Cài thư viện: `pip install -r "requirements.txt"`
2. Mở JupyterLab từ trong thư mục `lab05`: `jupyter lab`
3. Mở từng notebook, chọn Restart Kernel and Run All. Các notebook import `tictactoe.py` nên phải mở từ đúng thư mục này.
4. Bài 7 (`tictactoe_interactive.ipynb`): hai ô cuối hiện bàn cờ và chờ nhập nước đi (số ô 0–8) ngay dưới ô code.