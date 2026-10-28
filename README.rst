Free Python Games
=================

`Free Python Games`_ là bộ sưu tập các trò chơi Python miễn phí, phát hành theo
giấy phép Apache2, dành cho việc học tập và giải trí. Các trò chơi được viết
bằng mã Python đơn giản, được thiết kế để bạn thử nghiệm và chỉnh sửa. Bộ sưu
tập gồm nhiều phiên bản đơn giản hóa của các trò chơi arcade kinh điển.

Python là một trong năm ngôn ngữ lập trình phổ biến nhất thế giới và được cung
cấp miễn phí tại `Python.org <https://www.python.org/>`_. Python đi kèm một Thư
viện chuẩn (Standard Library) phong phú, được cài sẵn cùng bản cài đặt của bạn.
Trong Thư viện chuẩn có một module tên là Turtle, một cách phổ biến để giới
thiệu lập trình cho trẻ em. Turtle là một phần của ngôn ngữ lập trình Logo gốc,
do Wally Feurzig và Seymour Papert phát triển năm 1966. Tất cả các trò chơi
trong `Free Python Games`_ đều được viết bằng Python và module Turtle của nó.

Bắt đầu từ năm 2012, `Free Python Games`_ ra đời như một chương trình sau giờ
học nhằm dạy lập trình cho thanh thiếu niên ở khu vực nội thành. Mục tiêu là
vui chơi cũng quan trọng như học tập. Từ đó đến nay, các trò chơi đã được cải
tiến và sử dụng trong nhiều môi trường, từ lớp học đến các trại hè.

Các trò chơi chạy được ở bất cứ nơi nào cài được Python, bao gồm máy tính để
bàn chạy Windows, Mac OS hoặc Linux, cũng như các thiết bị cũ hoặc cấu hình
thấp như Raspberry Pi. Học sinh từ lớp 6 đến lớp 12 trên khắp nước Mỹ đã thích
thú học các chủ đề như mã hóa và chuyển động ném xiên thông qua các trò chơi.

Mỗi trò chơi hoàn toàn độc lập với các trò còn lại và có kèm chú thích cùng
một danh sách bài tập để học sinh thực hành. Sự sáng tạo và linh hoạt là điều
quan trọng. Không có cách đúng hay sai khi thêm một tính năng hay hành vi mới!
Bạn không thể biết trước học sinh sẽ hứng thú nhất với trò chơi nào.

.. _`Free Python Games`: https://grantjenks.com/docs/freegames/


Lời chứng thực
--------------

*"Tôi yêu Free Python Games vì các trò chơi rất vui, dễ hiểu và dễ thay đổi.
Giờ đây tôi thích tự làm trò chơi của riêng mình."*

-- Luke Martin, Học sinh

*"Free Python Games đã truyền cảm hứng và mang đến một sở thích mới cho con trai
chúng tôi. Cảm ơn rất nhiều vì đã giúp con làm quen với lập trình. Con rất vui!"*

-- Mary Lai, Phụ huynh

*"Free Python Games rất tuyệt vì thực sự thu hút học sinh và cho phép các em học
theo tốc độ của riêng mình."*

-- Rick Schertle, Giáo viên, Trường Steindorf STEAM

*"Free Python Games kết hợp vui chơi và học tập trong một môi trường linh hoạt,
giúp giảm áp lực của một chủ đề khó như lập trình."*

-- Brett Bymaster, Mục sư thanh niên, The River Church Community

*"Free Python Games rất phù hợp với học sinh, được tổ chức bài bản, linh hoạt
và khơi gợi sự tìm tòi, thấu hiểu."*

-- Terri Furton, Hiệu trưởng, Downtown College Prep


Tính năng
---------

- Chơi rất vui!
- Mã Python đơn giản
- Dễ cài đặt
- Thiết kế dành cho giáo dục
- Chỉ phụ thuộc vào Thư viện chuẩn của Python
- Đã được dùng trong hàng trăm giờ giảng dạy trên lớp
- Tài liệu đầy đủ
- Độ phủ kiểm thử 100%
- Phát triển trên Python 3.10
- Đã kiểm thử trên CPython 3.6, 3.7, 3.8, 3.9, 3.10
- Đã kiểm thử trên Linux, Mac OS X và Windows
- Kiểm thử bằng GitHub Actions

.. image:: https://github.com/grantjenks/free-python-games/workflows/integration/badge.svg
   :target: https://grantjenks.com/docs/freegames/


Bắt đầu nhanh
-------------

Cài đặt Free Python Games rất đơn giản với `pip
<https://pypi.python.org/pypi/pip>`_::

  $ python3 -m pip install freegames

Free Python Games hỗ trợ giao diện dòng lệnh (CLI). Xem trợ giúp của CLI bằng
lệnh::

  $ python3 -m freegames --help

CLI hỗ trợ ba lệnh: list, copy và show. Để xem danh sách tất cả các trò chơi,
chạy::

  $ python3 -m freegames list

Bạn có thể chơi bất kỳ trò nào trong danh sách bằng cách chạy module Python
tương ứng từ dòng lệnh. Để gọi module, hãy ghép "freegames" với tên của trò
chơi. Ví dụ, để chơi game "snake", chạy::

  $ python3 -m freegames.snake

Bạn có thể chỉnh sửa trò chơi bằng cách sao chép mã nguồn của nó. Lệnh copy sẽ
tạo một tệp Python trong thư mục hiện tại để bạn chỉnh sửa. Ví dụ, để sao chép
và chơi game "snake", chạy::

  $ python3 -m freegames copy snake
  $ python3 snake.py

Python có sẵn một trình soạn thảo văn bản tên là IDLE, cũng có thể chạy mã
Python. Để mở trình soạn thảo và chỉnh sửa game "snake", chạy::

  $ python3 -m idlelib.idle snake.py

Bạn cũng có thể xem tài liệu ngay trong trình thông dịch bằng hàm help có sẵn
của Python::

  >>> import freegames
  >>> help(freegames)

Free Python Games cũng cung cấp một script điểm vào (entry-point) để tương thích
với `pipx <https://pypa.github.io/pipx/>`_::

  $ pipx install freegames
  $ freegames play life


Các trò chơi miễn phí
---------------------

Paint
.....

`Paint`_ -- vẽ đường thẳng và hình khối trên màn hình. Nhấp chuột để đánh dấu
điểm bắt đầu của một hình, nhấp lần nữa để đánh dấu điểm kết thúc. Có thể chọn
các hình khối và màu sắc khác nhau bằng bàn phím.

.. image:: https://grantjenks.com/docs/freegames/_static/paint.gif
   :alt: Trò chơi Python miễn phí Paint

.. _`Paint`: https://grantjenks.com/docs/freegames/paint.html

Snake
.....

`Snake`_ -- trò chơi arcade kinh điển (rắn săn mồi). Dùng phím mũi tên để di
chuyển và ăn mồi màu xanh. Mỗi lần ăn mồi, con rắn dài thêm một đốt. Hãy tránh
tự ăn mình hoặc đâm ra ngoài khung!

.. image:: https://grantjenks.com/docs/freegames/_static/snake.gif
   :alt: Trò chơi Python miễn phí Snake

.. _`Snake`: https://grantjenks.com/docs/freegames/snake.html

Pacman
......

`Pacman`_ -- trò chơi arcade kinh điển. Dùng phím mũi tên để di chuyển và ăn hết
các chấm trắng. Cẩn thận với những con ma đỏ đang đi lang thang trong mê cung.

.. image:: https://grantjenks.com/docs/freegames/_static/pacman.gif
   :alt: Trò chơi Python miễn phí Pacman

.. _`Pacman`: https://grantjenks.com/docs/freegames/pacman.html

Cannon
......

`Cannon`_ -- chuyển động ném xiên. Nhấp chuột lên màn hình để bắn đạn đại bác.
Viên đạn sẽ làm nổ các quả bóng bay màu xanh trên đường bay. Hãy bắn nổ hết bóng
bay trước khi chúng bay ngang qua màn hình.

.. image:: https://grantjenks.com/docs/freegames/_static/cannon.gif
   :alt: Trò chơi Python miễn phí Cannon

.. _`Cannon`: https://grantjenks.com/docs/freegames/cannon.html

Connect
.......

`Connect`_ -- trò chơi Connect 4 (nối bốn). Nhấp vào một cột để thả đĩa. Người
chơi đầu tiên nối được bốn đĩa theo hàng dọc, hàng ngang hoặc đường chéo sẽ
thắng!

.. image:: https://grantjenks.com/docs/freegames/_static/connect.gif
   :alt: Trò chơi Python miễn phí Connect 4

.. _`Connect`: https://grantjenks.com/docs/freegames/connect.html

Flappy
......

`Flappy`_ -- trò chơi lấy cảm hứng từ Flappy Bird. Nhấp chuột lên màn hình để
vỗ cánh. Hãy tránh những con quạ đen khi bay ngang qua màn hình.

.. image:: https://grantjenks.com/docs/freegames/_static/flappy.gif
   :alt: Trò chơi Python miễn phí Flappy Bird

.. _`Flappy`: https://grantjenks.com/docs/freegames/flappy.html

Memory
......

`Memory`_ -- trò chơi ghép cặp số. Nhấp vào một ô để lật số. Ghép đúng hai số
giống nhau thì các ô sẽ biến mất và để lộ một bức hình.

.. image:: https://grantjenks.com/docs/freegames/_static/memory.gif
   :alt: Trò chơi Python miễn phí Memory

.. _`Memory`: https://grantjenks.com/docs/freegames/memory.html

Pong
....

`Pong`_ -- trò chơi arcade kinh điển. Dùng bàn phím để di chuyển thanh đỡ bóng
lên xuống. Người chơi đầu tiên để lọt bóng sẽ thua.

.. image:: https://grantjenks.com/docs/freegames/_static/pong.gif
   :alt: Trò chơi Python miễn phí Pong

.. _`Pong`: https://grantjenks.com/docs/freegames/pong.html

Simon Says
..........

`Simon Says`_ -- trò chơi trí nhớ kinh điển. Nhấp chuột lên màn hình để bắt đầu.
Quan sát chuỗi hiện ra rồi nhấp vào các ô theo đúng thứ tự đó. Mỗi lần bạn làm
đúng, chuỗi sẽ dài thêm một bước.

.. image:: https://grantjenks.com/docs/freegames/_static/simonsays.gif
   :alt: Trò chơi Python miễn phí Simon Says

.. _`Simon Says`: https://grantjenks.com/docs/freegames/simonsays.html

Tic Tac Toe
...........

`Tic Tac Toe`_ -- trò chơi kinh điển (cờ ca-rô 3x3). Nhấp chuột lên màn hình để
đặt X hoặc O. Nối được ba ô thẳng hàng là bạn thắng!

.. image:: https://grantjenks.com/docs/freegames/_static/tictactoe.gif
   :alt: Trò chơi Python miễn phí Tic Tac Toe

.. _`Tic Tac Toe`: https://grantjenks.com/docs/freegames/tictactoe.html

Tiles
.....

`Tiles`_ -- trò chơi xếp hình trượt số vào đúng vị trí. Nhấp vào ô nằm cạnh ô
trống để đổi chỗ. Bạn có thể xếp các ô đếm từ một đến mười lăm, từ trái sang
phải và từ dưới lên trên không?

.. image:: https://grantjenks.com/docs/freegames/_static/tiles.gif
   :alt: Trò chơi Python miễn phí Tiles

.. _`Tiles`: https://grantjenks.com/docs/freegames/tiles.html

Tron
....

`Tron`_ -- trò chơi arcade kinh điển. Dùng bàn phím để đổi hướng di chuyển của
người chơi Tron. Tránh chạm vào đường vạch do đối thủ vẽ ra.

.. image:: https://grantjenks.com/docs/freegames/_static/tron.gif
   :alt: Trò chơi Python miễn phí Tron

.. _`Tron`: https://grantjenks.com/docs/freegames/tron.html

Life
....

`Life`_ -- Trò chơi Sự sống (Game of Life) của Conway. Đây là mô hình tự động
tế bào kinh điển, không cần người chơi, do John Conway tạo ra năm 1970.

.. image:: https://grantjenks.com/docs/freegames/_static/life.gif
   :alt: Trò chơi Python miễn phí Game of Life

.. _`Life`: https://grantjenks.com/docs/freegames/life.html

Maze
....

`Maze`_ -- đi từ bên này sang bên kia (mê cung). Lấy cảm hứng từ bài viết `A
Universe in One Line of Code with 10 PRINT`_. Chạm vào màn hình để vạch một
đường đi từ phía này sang phía kia.

.. image:: https://grantjenks.com/docs/freegames/_static/maze.gif
   :alt: Trò chơi Python miễn phí Maze

.. _`Maze`: https://grantjenks.com/docs/freegames/maze.html
.. _`A Universe in One Line of Code with 10 PRINT`: https://www.makeartwithpython.com/blog/10-print-in-python/

Fidget
......

`Fidget`_ -- hoạt ảnh lấy cảm hứng từ con quay fidget spinner. Nhấp chuột lên
màn hình để làm con quay quay nhanh hơn.

.. image:: https://grantjenks.com/docs/freegames/_static/fidget.gif
   :alt: Trò chơi Python miễn phí Fidget Spinner

.. _`Fidget`: https://grantjenks.com/docs/freegames/fidget.html

Illusion
........

`Illusion`_ -- một ảo ảnh quang học.

.. image:: https://grantjenks.com/docs/freegames/_static/illusion.gif
   :alt: Trò chơi Python miễn phí Optical Illusion

.. _`Illusion`: https://grantjenks.com/docs/freegames/illusion.html

Typing
......

`Typing`_ -- luyện gõ phím khi các chữ cái rơi xuống màn hình.

.. image:: https://grantjenks.com/docs/freegames/_static/typing.gif
   :alt: Trò chơi Python miễn phí Typing

.. _`Typing`: https://grantjenks.com/docs/freegames/typing.html


Hướng dẫn sử dụng
-----------------

Phần này mô tả chi tiết hơn về chương trình học, API và cách phát triển, dành
cho những ai muốn tìm hiểu sâu.

* `Talk: Give the Gift of Python`_ -- bài nói "Trao tặng món quà Python"
* `Free Python Games Curriculum`_ -- chương trình học
* `Free Python Games API Reference`_ -- tài liệu tham khảo API
* `Free Python Games Development`_ -- hướng dẫn phát triển

.. _`Talk: Give the Gift of Python`: https://grantjenks.com/docs/freegames/give-gift-python.html
.. _`Free Python Games Curriculum`: https://grantjenks.com/docs/freegames/curriculum.html
.. _`Free Python Games API Reference`: https://grantjenks.com/docs/freegames/api.html
.. _`Free Python Games Development`: https://grantjenks.com/docs/freegames/development.html


Tài liệu tham khảo
------------------

* `Free Python Games Documentation`_ -- tài liệu
* `Free Python Games at PyPI`_ -- trang trên PyPI
* `Free Python Games at GitHub`_ -- trang trên GitHub
* `Free Python Games Issue Tracker`_ -- trang theo dõi lỗi

.. _`Free Python Games Documentation`: https://grantjenks.com/docs/freegames/
.. _`Free Python Games at PyPI`: https://pypi.python.org/pypi/freegames
.. _`Free Python Games at GitHub`: https://github.com/grantjenks/free-python-games
.. _`Free Python Games Issue Tracker`: https://github.com/grantjenks/free-python-games/issues


Giấy phép của Free Python Games
-------------------------------

Copyright 2017-2023 Grant Jenks

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License.  You may obtain a copy of the
License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.  See the License for the
specific language governing permissions and limitations under the License.
