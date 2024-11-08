# Create-collect
use rand::Rng;  fn gen_random_vector(n: usize) -> Vec&lt;i32> {     let mut rng = rand::thread_rng();     (0..n).map(|_| rng.gen_range(10..100)).collect() }  fn min_adjacent_sum(data: &amp;[i32]) -> (i32, usize, usize) {     let mut min_sum = i32::MAX;     let mut min_index = 0;
