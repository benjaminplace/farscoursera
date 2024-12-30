testthat::test_that("parse file", {
  x <- fars_summarize_years(2013) %>% filter(MONTH == 1) %>% pull(`2013`)
  testthat::expect_that(x, testthat::equals(2230))
})
