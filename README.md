# Convex hull :diamond_shape_with_a_dot_inside:

The convex hull is constructed by a <b>step-by-step input method</b>, namely <b>an incremental algorithm</b>. Each point is classified relative to the current shell. If the point is outside, there are reference points (the leftmost and rightmost) to which tangents are drawn from the point being checked. Thus, the shell is divided into two chains - near and far, the near chain is removed, the point being checked is added to the shell, the shell is redrawn.
<p><b>Algorithm complexity:</b>  O(n<sup>2</sup>)</p>

# Выпуклая оболочка :diamond_shape_with_a_dot_inside:
Выпуклая оболочка строится <b>методом пошагового ввода</b>, а именно <b>инкрементальным алгоритмом</b>. Каждая точка классифицируется относительно текущей оболочки. Если точка снаружи - находятся опорные точки (самая левая и  самая правая), к которым проводятся касательные от проверяемой точки. Тем самым оболочка делится на две цепочки - ближнюю и дальнюю, ближняя цепочка удаляется, проверяемая точка добавляется в оболочку, оболочка перерисовывается.
<p><b>Вычислительная сложность:</b>  O(n<sup>2</sup>)</p>


![risuno4ek1 (online-video-cutter com)](https://user-images.githubusercontent.com/106038032/172045239-71271fc6-cf2e-4ec5-8696-e7d8677714ed.gif)


